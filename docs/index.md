---
# home: true
sidebar: false
title: '大圣前端学习路线图'
---
# 大圣前端学习路线图
<!-- ['❌','✅','🔥','⭐'] -->

<roadmap  :data="[
  { title:'大圣前端路线图',x:400,y:20 ,download:true},
  { title:'✅HTML+CSS', y:130,link:'/fe/css.html',
    left:[
      ['HTML基础'],
      ['环境基本安装',[
        ['Vscode编辑器'],
        ['Chrome浏览器'],
      ]]
    ],right:[
      ['🔥常见布局'],
      ['🔥CSS基础',[
        ['选择器'],
        ['盒模型'],
        ['布局'],
        ['过渡和动画'],
      ]],
    ]
  } ,
  { title:'Javascript', link:'/fe/javascript.html',
    y:140,
    left:[
      ['✅语法入门',[
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
  { title:'🔥实战开发', link:'/fe/project.html',
   y:220,x:-162,
    left:[
      ['开发环境配置'],
      ['登录注册'],
      ['增删改查'],
      ['前后端交互'],
      ['Git代码管理'],
      ['调试代码'],
      ['✅和产品吵架'],
      ['(p)npm包管理'],
    ]
  },
  { title:'🔥面试', link:'/fe/interview.html',
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
  { title:'✅网站搭建',x:-162,y:170,link:'/server.html',
    left:[
      ['购买云机器'],
      ['购买域名'],
      ['nginx配置'],
      ['Linux'],
    ],
    right:[
      ['Vuepress'],
      ['❌Vitepress'],
      ['Dumi'],
      ['Gastby'],
    ]
  } ,
  { title:'进阶之路',y:100,
  } ,
  { title:'🔥Vue3',y:100,link:'/fe/vue.html',
    left:[
      ['入门',[-50],[
        ['清单应用'],
        ['模板语法'],
        ['组件基础'],
        ['表单'],
        ['Composition'],
        ['<script setup>'],
      ]],
      ['项目实战',[140],[
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
      ['源码',[140],[
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
  {title:'🔥框架设计理念',link:'fe/vue.html',
  y:280,
    left:[
      ['编译Compiler'],
      ['运行时Runtime'],
      ['template JSX'],
      ['响应式'],
    ],
    right:[
      ['Angular'],
      ['Svelte'],
      ['Solidjs'],
    ]
  },
  { title:'🔥React',y:190,link:'/fe/react.html',
    left:[
      ['入门',[-50],[
        ['cra脚手架'],
        ['清单应用'],
        ['JSX'],
        ['Hooks'],
        ['表单'],
        ['Ant Design'],
      ]],
      ['项目实战',[120],[
        ['redux dva'],
        ['react-router'],
        ['单元测试'],
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
      ['源码',[120],[
        ['虚拟Dom'],
        ['Fiber'],
        ['Hooks'],
        ['Render'],
        ['Reconciler'],
        ['Concurrent'],
        ['React Router'],
      ]],
    ]
  } ,
  { title:'Typescript',y:310, link:'/fe/typescript.html',
    left:[
      ['基础类型'],
      ['Interface'],
      ['复合类型'],
      ['操作符',[
        ['keyof'],
        ['in'],
      ]],
      ['函数类型'],
    ],
    right:[
      ['Vue+TS'],
      ['React+TS'],
      ['泛型<T>',[
        ['extends'],
        ['infer'],
        ['Partial'],
        ['Record'],
        ['Omit'],
      ]],
      ['网络接口类型'],
    ],
  } ,
  { title:'Node.js', y:200,link:'/fe/node.html',
    left:[
      ['Node入门'],
      ['Web开发',[
        ['Koa'],
        ['Eggjs'],
        ['Nest.js'],
      ]],
      ['文件流'],
      ['爬虫'],
    ],
    right:[
      ['数据库',[
        ['Mysql'],
        ['Mongodb'],
      ]],
      ['部署'],
      ['脚手架'],
      ['微前端'],
    ],
  } ,
  { title:'工程化', link:'/fe/fis.html',y:170,
    left:[
      ['初始化脚手架'],
      ['开发调试',[
        ['dev-server'],
        ['hmr'],
        ['mock'],
        ['proxy'],
      ]],
      ['构建'],
      ['测试',[20],[
        ['Jest单元测试'],
        ['E2E测试'],
      ]],
    ],
    right:[
      ['监控',[
        ['错误监控'],
        ['性能监控'],
      ]],
      ['发布'],
      ['安全',[
        ['XSS'],
        ['CSRF'],
      ]],
    ]
  } ,
  { title:'项目实战', link:'/fe/arch.html',
    y:230,
    left:[
      [
        'CSS架构设计',[
          ['sass'],
          ['bem'],
          ['动态主题'],
        ],
      ],
      ['框架封装'],
      ['前后端规范'],
      ['项目规范设计',[
        ['eslint'],
        ['git规范'],
        ['开发流程规范'],
      ]],
    ],
    right:[
      ['技术选型'],
      ['项目亮点',[
        ['什么算亮点'],
        ['数据量大'],
        ['研发效率'],
        ['线上稳定'],
      ]],
    ]
  } ,
    { title:'性能优化', link:'/fe/perf.html',y:200,
    left:[
      ['性能指标',[
        ['LCP'],
        ['TTI'],
        ['FP'],
      ]],
      ['lighthouse'],
      ['performance'],
    ],
    right:[
      ['优化策略',[
        ['减少代码体系'],
        ['缓存'],
        ['代码执行效率'],
      ]],
      ['性能监控'],
    ]
  } ,
  { title:'浏览器原理', link:'/fe/browser.html',y:140,
    left:[
      ['从输入URL到页面显示',[0,-80,200]],
      ['v8'],
      ['网络'],
    ],
    right:[
      ['页面渲染'],
      ['JS执行逻辑'],
    ]
  } ,
  { title:'软技能', link:'/fe/soft.html',
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
  { title:'⭐小程序', link:'/fe/miniapp.html',
    left:[
      ['小程序入门'],
      ['模板语法'],
      ['跨端框架',[
        ['Taro'],
        ['Uni-app'],
      ]],
      ['小程序进阶'],
    ],
    right:[
      ['云开发',[
        ['云函数'],['云数据库'],['云存储'],
      ]],
      ['支付'],
      ['小程序原理'],
    ]
  } ,
  { title:'🔥计算机网络', link:'/it/internet.html',y:120,
    left:[
      ['互联网如何工作'],
      ['网络协议分层'],
    ],
    right:[
      ['网络安全'],
      ['什么是HTTP'],
      ['什么是TCP'],
    ]
  } ,
  { title:'🔥算法和数据结构', link:'/it/algorithm.html',y:200,
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
      ['React中的算法'],
    ]
  } ,
  { title:'⭐App开发', link:'/fe/app.html',y:200,
    left:[
      ['React Native'],
      ['❌Weex'],
    ],
    right:[
      ['Flutter'],
    ],
  } ,
  { title:'⭐热门技术', link:'/fe/hot.html',
    left:[
      ['Electron'],
      ['Rust'],
      ['Go'],
      ['IDE'],
      ['Web'],
    ],
    right:[
      ['可视化',[
        ['Echarts','Antv']
      ]],
      ['Rust'],
      ['Go',[
        ['esbuild']
      ]],
      ['Web Assembly'],
    ],
  } ,
  {title:'终身成长'},
]"/>
<!-- https://mo.fish/ -->
<!-- https://duomoyu.com/ -->