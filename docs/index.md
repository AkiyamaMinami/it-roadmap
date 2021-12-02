---
home: true

---
<!-- ['❌','✅','🔥','⭐'] -->

<roadmap :height="5000" :data="[
  { title:'大圣前端路线图',x:400,y:20 },
  { title:'⭐HTML+CSS', y:130,link:'/fe/css',
    left:[
      ['HTML基础'],
      ['环境基本安装',[
        ['Vscode编辑器'],
        ['Chrome浏览器'],
      ]]
    ],right:[
      ['CSS常见布局'],
      ['CSS基础',[
        ['选择器'],
        ['盒模型'],
        ['布局'],
        ['过渡和动画'],
      ]],
    ]
  } ,
  { title:'Javascript', link:'/fe/javascript',
    y:150,
    left:[
      ['语法入门',[
        ['ES6语法'],
        ['Dom'],
        ['🔥红宝书'],
        ['高频面试题'],
      ]],
    ],
    right:[
      ['JS设计模式'],
      ['🔥JS语法进阶',[
        ['作用域  闭包'],
        ['this   原型链'],
        ['Promise'],
        ['函数和递归'],
        ['面向对象'],
      ]]
    ]
  } ,
  { title:'🔥实战开发', link:'/fe/project',
   y:200,x:-162,
    left:[
      ['登录注册'],
      ['增删改查'],
      ['前后端交互'],
      ['Git代码管理'],
      ['调试代码'],
      ['✅和产品吵架'],
      ['(p)npm包管理'],
    ]
  },
  { title:'🔥面试', link:'/fe/interview',
    y:10,x:325,
    right:[
      ['如何写简历'],
      ['如何描述项目'],
      ['🔥如何谈钱'],
      ['高频面试题'],
      ['如何选择Offer'],
      ['如何离职'],
    ]
  } ,
  { title:'进阶之路',x:-162,y:85,
  } ,
  { title:'Vue3',y:200,link:'/fe/vue',
    left:[
      ['入门',[-50],[
        ['清单应用'],
        ['模板语法'],
        ['组件基础'],
        ['表单'],
        ['Composition'],
        ['<script setup>'],
      ]],
      ['项目实战',[150],[
        ['Vuex Pinia'],
        ['vue-router'],
        ['单元测试'],
        ['JSX'],
        ['性能优化'],
        ['use工具库'],
        ['权限路由'],
        ['开发规范'],
        ['SSR框架Nuxt'],
      ]],
    ],
    right:[
      ['组件化设计',[-50],[
        ['组件库推荐'],
        ['组件三要素'],
        ['基础组件'],
        ['表单组件'],
        ['弹窗组件'],
        ['表格组件'],
        ['组件文档'],
      ]],
      ['源码',[150],[
        ['Vue3新特性'],
        ['响应式原理'],
        ['虚拟Dom'],
        ['Runtime'],
        ['Compiler优化'],
        ['Vue-router源码'],
        ['Vite源码'],
      ]],
    ]
  } ,
  { title:'React',y:600,link:'/fe/react',
    left:[
      ['入门',[-50],[
        ['cra脚手架'],
        ['清单应用'],
        ['JSX'],
        ['Hooks'],
        ['表单'],
        ['Hooks'],
        ['<script setup>'],
      ]],
      ['项目实战',[150],[
        ['Vuex Pinia'],
        ['vue-router'],
        ['调试工具'],
        ['单元测试'],
        ['JSX'],
        ['性能优化'],
        ['权限路由'],
        ['use工具库'],
        ['全栈框架Next.js'],
      ]],
    ],
    right:[
      ['组件化设计',[-50],[
        ['组件三要素'],
        ['基础组件'],
        ['表单组件'],
        ['弹窗组件'],
        ['表格组件'],
        ['组件文档'],
      ]],
      ['源码',[150],[
        ['Vue3新特性'],
        ['响应式原理'],
        ['虚拟Dom'],
        ['Runtime'],
        ['Compiler优化'],
        ['Vue-router源码'],
        ['Vite源码'],
      ]],
    ]
  } ,
  { title:'软技能', link:'/fe/javascript',y:550,
    left:[
      ['技术管理'],
      ['影响力'],
      ['沟通',[
        ['绩效沟通']
      ]],
    ],
    right:[
      ['职业规划',[
        ['技术管理'],
        ['技术管理'],
        ['技术管理'],
        ['技术管理'],
      ]],
      ['运营'],
      ['产品能力'],
    ]
  },
  { title:'Typescript', link:'/fe/javascript'} ,
  { title:'小程序', link:'/fe/javascript'} ,
  { title:'桌面应用开发', link:'/fe/javascript'} ,
  { title:'性能优化', link:'/fe/javascript'} ,
  { title:'测试', link:'/fe/javascript'} ,
  { title:'工程化', link:'/fe/javascript'} ,
  { title:'Node.js', link:'/fe/javascript'} ,
  { title:'小程序', link:'/fe/javascript'} ,
  { title:'计算机基础', link:'/fe/javascript'},
  { title:'计算机网络', link:'/it/network',
    left:[
      ['互联网如何工作'],
      ['什么是HTTP'],
    ]
  } ,
  { title:'算法和数据结构', link:'/fe/algorithm',
    left:[
      ['排序'],
      ['搜索'],
      ['二分'],
      ['递归'],
      ['回溯'],
      ['贪心算法'],
      ['动态规划'],
    ],
    right:[
      ['数组'],
      ['链表'],
      ['树'],
      ['堆栈'],
      ['图'],
      ['Vue中的算法'],
    ]
  } ,
  { title:'项目实战', link:'/fe/project',
    y:200,
    left:[
      [
        'CSS架构设计',[
          ['less,sass\nstylus'],
          ['函数'],
          ['动态主题'],
        ]
      ]
    ]
  } ,
  { title:'热门技术', link:'/fe/javascript'} ,
  {title:'终身成长'}
]"/>
