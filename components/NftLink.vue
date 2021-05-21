<template>
  <span class="has-text-weight-bold">
    <next-link
      :to="{
        name: 'nft-detail',
        params: { type: type, contract: contract, id: id },
      }"
    >
      {{ name }}
    </next-link>
  </span>
</template>

<script>
export default {
  name: "NftLink",
  props: ["name", "type", "contract", "id"],
};
</script>
