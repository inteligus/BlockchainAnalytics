<template>
  <div class="idb-block">
    <div class="idb-block-title">
      <h2>Quill Editor</h2>
    </div>
    <div class="idb-block-content">
      <quill-editor v-model="content"
                  ref="myQuillEditor"
                  :options="editorOption"
                  @blur="onEditorBlur($event)"
                  @focus="onEditorFocus($event)"
                  @ready="onEditorReady($event)">
      </quill-editor>
    </div>
  </div>
</template>

<style lang="scss">
  .ql-container {
    min-height: 300px;
  }
</style>
<script>
export default {
  data: function () {
    return {
      content: '<h2>I am Example</h2>',
      editorOption: {
        // some quill options
      }
    }
  },
  methods: {
    onEditorBlur (editor) {
      console.log('editor blur!', editor)
    },
    onEditorFocus (editor) {
      console.log('editor focus!', editor)
    },
    onEditorReady (editor) {
      console.log('editor ready!', editor)
    },
    onEditorChange ({ editor, html, text }) {
      console.log('editor change!', editor, html, text)
      this.content = html
    }
  },
  computed: {
    editor () {
      return this.$refs.myQuillEditor.quill
    }
  },
  mounted () {
    // you can use current editor object to do something(quill methods)
    console.log('this is current quill instance object', this.editor)
  }
}
</script>
