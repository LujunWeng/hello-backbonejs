# Hello Backbone - A tutorial

**Hello Backbone** is a simple [Backbone.js](http://documentcloud.github.com/backbone) tutorial comprised of self-explanatory "hello world" examples of increasing complexity. It was designed to provide a smoother transition from zero to the popular [Todos example](http://documentcloud.github.com/backbone/docs/todos.html).

Use:

    docco *.js

in the root directory to compile the docs using [Docco](http://jashkenas.github.com/docco/).

See it in action:
http://arturadib.github.com/hello-backbonejs/

# Update

The original version was made 2 years ago. Some usages of backbone
seems a little inappropriate today. Therefore, I made some modifications to
match today's backbone. The main changes are as follows:

1. use `el: 'body'` instead of `el: $('body')`
2. use `this.$el` directly instead of `$(this.el)`
3. remove dummy `Backbone.sync.` It seems that `model.destroy()` would not
raise any error
4. use `each` method of `collection` instead of using it through `underscore`
5. change `model.bind()` to `model.on()`
6. update versions of backbone and underscore

The "See it in action" link does not work. So this is mine:

http://lujunweng.github.io/hello-backbonejs/

