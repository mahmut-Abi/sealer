```
st=>start: web 页面
op=>operation: 选择基础架构平台
cond=>condition: 判断框(是或否?)
sub1=>subroutine: 子流程
sub2=>subroutine: 子流程2
sub3=>subroutine: 子流程2
io=>inputoutput: 输入输出框
e=>end: 结束框

st->op->cond
cond(libvirt)->sub1->io->e
cond(ustack)->sub2(right)->op
cond(metal)->sub3(left)->op

```
