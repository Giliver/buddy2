这个代码相比云风实现的版本要清晰许多，没有回溯，状态维护也一目了然。

本想着 `index_to_offset` 会是一件很复杂的事情，一个数学表达式就搞定 `offset = (index + 1) * node_size - self->size;`
