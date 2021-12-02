---
home: true

---
<!-- ['❌','✅','🔥','⭐'] -->

<roadmap :height="5000" :data="[
  { title:'大圣前端路线图',x:400,y:20 },
  { title:'⭐HTML+CSS', y:150,link:'/fe/css',
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
    y:170,
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
   y:220,x:-162,
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
      ['如何离职'],
    ]
  } ,
  { title:'进阶之路',x:-162,y:100,
  } ,
  { title:'Vuejs',y:100,link:'/fe/vue',
    left:[
      ['响应式'],
      ['组件化'],
      ['element3',[
        ['1']
      ]],
    ]
  } ,
  { title:'Reactjs',y:200,link:'/fe/react',
  right:[
    ['Hooks'],
    ['虚拟Dom'],
    ['Ant Design'],
  ]} ,
  { title:'软技能', link:'/fe/javascript',y:150,
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
