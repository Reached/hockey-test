<template>
    <Page>
        <StackLayout>
            <SegmentedBar>
                <SegmentedBarItem title="First" />
                <SegmentedBarItem title="Second" />
                <SegmentedBarItem title="Third" />
            </SegmentedBar>
        </StackLayout>
    </Page>
</template>

<script>
  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
