<template>
    <section class="post-list">
      <PostPreview
        :id="1"
        title="Post title id 1"
        previewText="Preview Text id 1"
        thumbnail="https://www.gupy.io/hubfs/HR-tech.jpg"
      />
      <PostPreview
        :id="2"
        title="Post title id 2"
        previewText="Preview Text id 2"
        thumbnail="https://bedu.tech/wp-content/uploads/2019/12/3066754_optimized-scaled.jpg"
      />
      <PostPreview
        :id="3"
        title="Post title id 3"
        previewText="Preview Text id 3"
        thumbnail="https://braziljournal.s3.amazonaws.com/covers/cc0ca864-92e6-d739-7cee-7fd944d9ae4e.jpg?v=1620083342"
      />
    </section>
</template>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>