<template>
  <div class="q-mb-md w-full">
    <h3>
      {{ title }}
    </h3>

    <div class="flex items-center justify-between no-wrap q-mb-md q-mt-sm">
      <p class="q-ma-none q-mr-md text-body1 text-grey-8">
        {{ subtitle }}
      </p>

      <slot name="right" />
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionTitle",

  props: {
    title: {
      type: String,
      required: true,
    },

    subtitle: {
      type: String,
      default: "",
    },
  },
};
</script>
