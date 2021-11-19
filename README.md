# fix-touchpad-click-once-but-change-value-twice
el-input-number解决鼠标单击触发一次更改，但是触摸板单击一次触发两次更改的问题

使用方式:

//全局引入element-ui,可以覆盖element-ui原装的input-number
import Vue from 'vue';
import ElementUI from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';
import ElInputNumber from '@ui/ElInputNumber/ElInputNumber'

Vue.use(ElementUI);
Vue.component(ElInputNumber.name,ElInputNumber);
