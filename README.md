# vue-bootstrap4-modal
Vue Bootstrap 4 Modal Component

## Usage

``` vue
<modal title="Hello World" :is-small="true" v-if="show_modal" @close="show_modal = false">
  <div class="modal-body">
    Hello.
  </div>
  
  <div class="modal-footer">
    <button type="button" class="btn btn-secondary" @click="show_modal = false">Cancel</button>
    <button type="button" class="btn btn-primary" @click="alert('Hello!')">Hello Sir</button>
  </div>
</modal>
```
