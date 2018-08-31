<template>
    <FlexboxLayout padding="10" flexDirection="column">
        <Label text="Title Something" fontWeight="bold"/>
        <Label :text="item.text" textWrap="true"/>
    </FlexboxLayout>
</template>
<script>
  export default {
    name: 'ListItemComponent',
    props: {
      item: {}
    },
  }
</script>
