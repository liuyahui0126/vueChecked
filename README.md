# vueChecked

###    数组引用值踩坑

###  ![]./screenPics/plus.png

之前数组是引用值，直接对数组进行操作界面不会变化，因为指向地址没发生变化。   
在用concat方法拷贝出一个数组的时候，对这个数组进行改变，再重新赋值回原数组，数组的引用值发生变化而实现效果
