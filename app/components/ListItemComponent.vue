<template functional>
    <FlexboxLayout padding="10" flexDirection="column">
        <Label text="Title Something" fontWeight="bold"/>
        <Label :text="props.item.text" textWrap="true"/>
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
