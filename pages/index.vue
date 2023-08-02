<template>
  <div class="container-wrapper text-base">
    <div class="header-wrapper px-6 flex items-center relative">
      <a href="/" class="pr-2"
        ><img
          src="https://www.udemy.com/staticx/udemy/images/v7/logo-udemy.svg"
          width="91"
          height="34"
          alt=""
      /></a>
      <div class="relative cursor-pointer">
        <div class="px-3 my-3 text-sm header-height">类别</div>
      </div>
      <div class="search-wrapper relative mx-3 flex items-center pr-4">
        <i class="icon-search"></i>
        <input
          class="search-input pl-1"
          type="text"
          placeholder="搜索任何内容"
        />
      </div>
      <div class="relative cursor-pointer">
        <div class="px-3 my-3 text-sm header-height">Udemy Business</div>
      </div>
      <div class="relative cursor-pointer">
        <div class="px-3 my-3 text-sm header-height">在 Udemy 上授课</div>
      </div>
      <div class="relative cursor-pointer">
        <div class="px-3 my-3 text-sm header-height flex items-center">
          <i class="icon-cartFull"></i>
        </div>
      </div>
      <div
        class="btn-wrapper btn-width ml-2 flex justify-center items-center font-bold cursor-pointer"
      >
        <span class="px-3">请登录</span>
      </div>
      <div
        class="btn-wrapper btn-width btn-signup ml-2 flex justify-center items-center font-bold cursor-pointer"
      >
        <span class="px-3">注册</span>
      </div>
      <div
        class="btn-wrapper ml-2 flex justify-center items-center font-bold cursor-pointer"
      >
        <i class="icon-language"></i>
      </div>
    </div>
    <div class="top-hang">
      <div class="py-2 px-4">
        <p class="font-bold mb-1">
          The Complete Python Bootcamp From Zero to Hero in Python
        </p>
        <div class="flex">
          <a href="/" class="flex mr-2">
            <span class="mr-1 color-f3ca8c text-sm font-bold">4.6</span>
            <img
              src="~/static/icon-star.png"
              style="height: 18px"
              alt=""
              class="mr-0.5"
            />
            <span class="color-cec0fc underline">(472786 个评分)</span>
          </a>
          <span>1759807 名学生</span>
        </div>
      </div>
    </div>
    <div class="relative">
      <div class="top-container py-8">
        <div class="container-main">
          <div class="breadcrumb font-bold flex items-center mb-3">
            <span class="cursor-pointer">开发</span>
            <img
              src="~/static/icon-right.png"
              class="px-1 py-1"
              width="20"
              height="20"
              alt=""
            />
            <span class="cursor-pointer">Programming Languages</span>
            <img
              src="~/static/icon-right.png"
              class="px-1 py-1"
              width="20"
              height="20"
              alt=""
            />
            <span class="cursor-pointer">Python</span>
          </div>
          <div class="innertext-container">
            <div class="lead-title font-bold mb-2">
              The Complete Python Bootcamp From Zero to Hero in Python
            </div>
            <div class="sub-title mb-4">
              Learn Python like a Professional Start from the basics and go all
              the way to creating your own applications and games
            </div>
            <div class="score mb-2 flex">
              <a href="/" class="flex mr-2">
                <span class="mr-1 color-f3ca8c text-sm font-bold">4.6</span>
                <img src="~/static/score.png" alt="" class="mr-0.5" />
                <span class="color-cec0fc underline">(472786 个评分)</span>
              </a>
              <span>1,759,807 个学生</span>
            </div>
            <div class="mb-2">
              <span class="">创建者</span>
              <a href="/" class="color-cec0fc underline"> Jose Portilla </a>
            </div>
            <div class="mb-2 flex items-center">
              <img
                src="~/static/change.png"
                alt=""
                style="height: 20px"
                class="mr-2"
              />
              <span class="mr-4">上次更新时间：2023年7月</span>
              <img
                src="~/static/language-sm.png"
                style="height: 20px"
                alt=""
                class="mr-2"
              />
              <span class="mr-4">英语</span>
              <img
                src="~/static/keyboard.png"
                style="height: 20px"
                alt=""
                class="mr-2"
              />
              <span class="mr-4"
                >简体中文 [自动], 英语 [自动] ,<a
                  href="/"
                  class="color-cec0fc underline"
                  >还有 14</a
                ></span
              >
            </div>
          </div>
        </div>
      </div>
      <div class="body-wrapper">
        <div class="container-main relative">
          <div class="content-wrapper">
            <div class="will-get">
              <h2 class="text-2xl ml-6 mb-4">你将会学到的</h2>
              <ul
                class="ml-6 mr-6 flex justify-between flex-wrap"
                :class="{ 'show-more-mask': !textShow }"
              >
                <li>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >You will learn how to leverage the power of Python to
                      solve tasks.</span
                    >
                  </div>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >You will build games and programs that use Python
                      libraries.</span
                    >
                  </div>
                </li>
                <li>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >You will be able to use Python for your own work problems
                      or personal projects.</span
                    >
                  </div>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >You will create a portfolio of Python based projects you
                      can share.</span
                    >
                  </div>
                </li>
                <li>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Learn to use Python professionally, learning both Python
                      2 and Python 3!</span
                    >
                  </div>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Create games with Python, like Tic Tac Toe and
                      Blackjack!</span
                    >
                  </div>
                </li>
                <li>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Learn advanced Python features, like the collections
                      module and how to work with timestamps!</span
                    >
                  </div>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Learn to use Object Oriented Programming with
                      classes!</span
                    >
                  </div>
                </li>
                <li>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Understand complex topics, like decorators.</span
                    >
                  </div>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Understand how to use both the Jupyter Notebook and
                      create .py files</span
                    >
                  </div>
                </li>
                <li>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Get an understanding of how to create GUIs in the Jupyter
                      Notebook system!</span
                    >
                  </div>
                  <div class="py-1 flex">
                    <i class="icon-success"></i>
                    <span class="ml-4"
                      >Build a complete understanding of Python from the ground
                      up!</span
                    >
                  </div>
                </li>
              </ul>
              <div class="ml-6 color-5624d0 font-bold show-btn cursor-pointer">
                <span
                  class="show-more-text"
                  v-show="!textShow"
                  @click="textShow = true"
                  >显示更多</span
                >
                <span
                  class="show-less-text"
                  v-show="textShow"
                  @click="textShow = false"
                  >显示更少</span
                >
              </div>
            </div>
            <div class="about-provide">
              <div class="provide-header">
                <p class="font-bold text-base">
                  顶级公司为他们的员工提供这门课程
                </p>
                <p class="mt-1">
                  此课程被选入我们受全球企业信赖的最受好评的课程系列。<span
                    class="color-5624d0 underline cursor-pointer"
                    >了解更多</span
                  >
                </p>
              </div>
              <div class="flex justify-between mt-6">
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/nasdaq-dark.svg"
                  alt=""
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/volkswagen-dark.svg"
                  alt=""
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/box-dark.svg"
                  alt=""
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/netapp-dark.svg"
                  alt=""
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/eventbrite-dark.svg"
                  alt=""
                />
              </div>
            </div>
            <div class="mb-8">
              <div class="code-wrapper">
                <div class="flex flex-col justify-center basis-1/3">
                  <h2 class="font-bold text-2xl">代码练习</h2>
                  <p class="pt-4 pb-6 color-6a6f73 text-sm">
                    本课程包括我们更新的代码练习，因此您可以在学习过程中演练所掌握的技能。
                  </p>
                  <a href="" class="color-5624d0 underline pt-4">查看演示</a>
                </div>
                <img src="~/static/coding-exercises.png" class="ml-8" alt="" />
              </div>
            </div>
            <div class="mb-8">
              <h2 class="font-bold text-2xl mb-4">课程内容</h2>
              <div class="flex justify-between">
                <p class="my-2">
                  23 个章节 • 156 个讲座 • 总时长 22 小时 13 分钟
                </p>
                <div class="my-2 color-5624d0 cursor-pointer">
                  <span v-show="!collapseShow" @click="onOpenCollapse"
                    >展开所有章节</span
                  >
                  <span v-show="collapseShow" @click="onCloseCollapse"
                    >折叠所有章节</span
                  >
                </div>
              </div>
              <div class="collapse-wrapper">
                <div
                  class="collapse-item"
                  v-for="item in contentList"
                  :key="item.id"
                >
                  <div class="collapse-item-th" @click="onChildrenChange(item.id)">
                    <div class="flex items-center">
                      <i class="icon-down"></i>
                      <span class="font-bold text-base ml-3">{{
                        item.name
                      }}</span>
                    </div>
                    <span>{{ item.time }}</span>
                  </div>
                  <div class="collapse-item-td" v-show="openChildrenIds.includes(item.id)">
                    <div class="py-2 flex" v-for="children in item.children" :key="children.id">
                      <img :src="children.src" style="width:20px;height:20px" alt="" />
                      <div class="flex flex-1 justify-between ml-4">
                        <div>
                          <div class="flex items-center">
                            <span :class="[children.underline?'underline color-5624d0': '']">{{children.name}}</span>
                            <img
                               src="~/static/icon-down3.png"
                              class="cursor-pointer ml-2"
                              :class="{'icon-down-open': openSubNames.includes(children.subName)}"
                              alt=""
                              v-if="children.subName"
                              @click="onSubNameChange(children.subName)"
                            />
                          </div>
                          <p class="pt-2 color-6a6f73" v-show="openSubNames.includes(children.subName)">
                            {{children.subName}}
                          </p>
                        </div>
                         <div>
                          <span class="underline color-5624d0 mr-8" v-show="children.underline">预览</span>
                          <span>{{children.time}}</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container-main">
        <div
          class="sider-wrapper"
          :class="{ 'sidebar-container--fixed': sideShow }"
        >
          <img src="~/static/preview.png" v-show="!sideShow" alt="" />
          <div class="px-6 py-6 sider-main">
            <div class="flex items-center">
              <span class="price-now">US$24.99</span>
              <span class="text-base color-6a6f73"><s>US$94.99</s></span>
            </div>
            <p class="text-base py-2 color-6a6f73">74% 折扣</p>
            <p class="flex items-center color-b32d0f">
              <img src="~/static/time.png" alt="" /> 此优惠价格仅剩
              <span class="font-bold">5 小时</span>！
            </p>
            <div class="btn-cart mt-4 mb-2 btn-style1">添加至购物车</div>
            <div class="btn-cart mb-2 btn-style2">立即购买</div>
            <p class="mt-4 mb-2 text-xs text-center">30 天退款保证</p>
            <div class="including-wrapper pt-4">
              <h2 class="text-base mb-2 font-bold">本课程包括：</h2>
              <p class="py-1 flex items-center">
                <img src="~/static/cluding-type1.png" alt="" />
                <span class="ml-4">22 小时 长的随选视频</span>
              </p>
              <p class="py-1 flex items-center">
                <img src="~/static/cluding-type2.png" alt="" />
                <span class="ml-4">19 个代码练习</span>
              </p>
              <p class="py-1 flex items-center">
                <img src="~/static/cluding-type3.png" alt="" />
                <span class="ml-4">15 篇文章</span>
              </p>
              <p class="py-1 flex items-center">
                <img src="~/static/cluding-type4.png" alt="" />
                <span class="ml-4">在移动设备和电视上观看</span>
              </p>
              <p class="py-1 flex items-center">
                <img src="~/static/cluding-type5.png" alt="" />
                <span class="ml-4">完整的永久访问权</span>
              </p>
              <p class="py-1 flex items-center">
                <img src="~/static/cluding-type6.png" alt="" />
                <span class="ml-4">结业证书</span>
              </p>
            </div>
            <div class="flex justify-between font-bold">
              <div class="cursor-pointer underline underline-offset-4">
                分享
              </div>
              <div class="cursor-pointer underline underline-offset-4">
                将该课程作为礼物赠送
              </div>
              <div class="cursor-pointer underline underline-offset-4">
                使用优惠券
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-wrapper">
      <div class="footer-container">
        <div class="flex">
          <div class="link-wrap">
            <div class="py-1"><a href="" class="hover:underline">Udemy Business</a></div>
            <div class="py-1"><a href="" class="hover:underline">在 Udemy 上授课</a></div>
            <div class="py-1"><a href="" class="hover:underline">获取应用程序</a></div>
            <div class="py-1"><a href="" class="hover:underline">关于我们</a></div>
            <div class="py-1"><a href="" class="hover:underline">联系我们</a></div>
          </div>
          <div class="link-wrap">
            <div class="py-1"><a href="" class="hover:underline">职业生涯</a></div>
            <div class="py-1"><a href="" class="hover:underline">博客</a></div>
            <div class="py-1"><a href="" class="hover:underline">帮助和支持</a></div>
            <div class="py-1"><a href="" class="hover:underline">营销联盟</a></div>
            <div class="py-1"><a href="" class="hover:underline">投资者</a></div>
          </div>
          <div class="link-wrap">
            <div class="py-1"><a href="" class="hover:underline">条款</a></div>
            <div class="py-1"><a href="" class="hover:underline">隐私政策</a></div>
            <div class="py-1"><a href="" class="hover:underline">Cookie 设置</a></div>
            <div class="py-1"><a href="" class="hover:underline">网站地图</a></div>
            <div class="py-1"><a href="" class="hover:underline">无障碍声明</a></div>
          </div>
        </div>
        <div class="foot-btn">
          <i class="icon-language2 mr-1"></i>中文(简体)
        </div>
        <div class="logo-and-copyright">
          <img src="~/static/logo-udemy-inverted.svg" width="91" height="34" alt="">
          <span class="text-xs">© 2023 Udemy, Inc.</span>
        </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      textShow: false,
      sideShow: false,
      collapseShow: false,
      contentList: [
        {
          id: 1,
          name: "Course Overview",
          time: "5 个讲座 • 19 分钟",
          children: [
            {
              id: "1-1",
              src: require('../static/cluding-type3.png'),
              name: "Auto-Welcome Message",
              subName: "Welcome to the Complete Python Bootcamp",
              underline: false,
              time: "00:44",
            },
            {
              id: "1-2",
              src: require('../static/cluding-type1.png'),
              name: "Course Introduction",
              subName: "The Complete Python Bootcamp.",
              underline: true,
              time: "06:39",
            },
            {
              id: "1-3",
              src: require('../static/cluding-type1.png'),
              name: "Course Curriculum Overview",
              subName: "Learn about all the content in the course! ",
              underline: false,
              time: "04:00",
            },
            {
              id: "1-4",
              src: require('../static/cluding-type1.png'),
              name: "Why Python?",
              subName:
                "Learn why you should learn Python and what you can use it for",
              underline: false,
              time: "05:17",
            },
            {
              id: "1-5",
              src: require('../static/cluding-type3.png'),
              name: "Course FAQs",
              subName: "Continually updated Text Document with Course FAQs.",
              underline: false,
              time: "02:33",
            },
          ],
        },
        {
          id: 2,
          name: "Python Setup",
          time: "5 个讲座 • 54 分钟",
          children: [
            {
              id: "2-1",
              src: require('../static/cluding-type1.png'),
              name: "Command Line Basics",
              subName: "In order to learn about Python 3, we first need to learn about the command line! Let's get started!",
              underline: false,
              time: "08:15",
            },
            {
              id: "2-2",
              src: require('../static/cluding-type1.png'),
              name: "Installing Python (Step by Step)",
              subName: "Learn how to install Python on to your computer in an easy step by step guide!",
              underline: true,
              time: "23:08",
            },
            {
              id: "2-3",
              src: require('../static/cluding-type1.png'),
              name: "Running Python Code",
              subName: "Let's talk about how to run Python 3 code!",
              underline: false,
              time: "17:50",
            },
            {
              id: "2-4",
              src: require('../static/cluding-type1.png'),
              name: "Getting the Notebooks and the Course Material",
              subName:
                "Let's talk about how to get the notebooks for the course and the course material. Check out the resource links for this lecture!",
              underline: false,
              time: "02:22",
            },
            {
              id: "2-5",
              src: require('../static/cluding-type3.png'),
              name: "Git and Github Overview (Optional)",
              subName: "Learn how git version control and create you GitHub account to show off your projects! ",
              underline: false,
              time: "02:49",
            },
          ],
        },
        {
          id: 3,
          name: "Python Object and Data Structure Basics",
          time: "21 个讲座 • 2 小时 2 分钟",
          children: [
            {
              id: "3-1",
              src: require('../static/cluding-type1.png'),
              name: "Introduction to Python Data Types",
              subName: "Learn the basics of data types in Python 3.",
              underline: false,
              time: "04:02",
            },
            {
              id: "3-2",
              src: require('../static/cluding-type1.png'),
              name: "Python Numbers",
              subName: "Learn the basic number data types in Python, such as integers and floats.",
              underline: true,
              time: "23:08",
            },
            {
              id: "3-3",
              src: require('../static/cluding-type2.png'),
              name: "Numbers: Simple Arithmetic",
              subName: "",
              underline: false,
              time: "1 问题",
            },
          ],
        },
        {
          id: 4,
          name: "Python Comparison Operators",
          time: "2 个讲座 • 9 分钟",
          children: [
            {
              id: "4-1",
              src: require('../static/cluding-type1.png'),
              name: "Comparison Operators in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "03:26",
            },
            {
              id: "4-2",
              src: require('../static/cluding-type1.png'),
              name: "Chaining Comparison Operators in Python with Logical Operators",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "05:42",
            },
            {
              id: "4-3",
              src: require('../static/cluding-type2.png'),
              name: "Comparison Operators Quiz",
              subName: "Test your knowledge on Comparison Operators",
              underline: false,
              time: "5 问题",
            },
          ],
        },
        {
          id: 5,
          name: "Python Comparison Operators",
          time: "7 个讲座 • 1 小时 15 分钟",
          children: [
            {
              id: "5-1",
              src: require('../static/cluding-type1.png'),
              name: "If Elif and Else Statements in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "09:06",
            },
            {
              id: "5-2",
              src: require('../static/cluding-type1.png'),
              name: "For Loops in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: true,
              time: "18:17",
            },
            {
              id: "5-3",
              src: require('../static/cluding-type1.png'),
              name: "Comparison Operators Quiz",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "10:35",
            },
          ],
        },
        {
          id: 6,
          name: "Methods and Functions",
          time: "18 个讲座 • 2 小时 54 分钟",
          children: [
            {
              id: "6-1",
              src: require('../static/cluding-type1.png'),
              name: "If Elif and Else Statements in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "09:06",
            },
            {
              id: "6-2",
              src: require('../static/cluding-type1.png'),
              name: "For Loops in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: true,
              time: "18:17",
            },
            {
              id: "6-3",
              src: require('../static/cluding-type1.png'),
              name: "Comparison Operators Quiz",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "10:35",
            },
          ],
        },
        {
          id: 7,
          name: "Milestone Project - 1",
          time: "9 个讲座 • 1 小时 40 分钟",
          children: [
            {
              id: "7-1",
              src: require('../static/cluding-type1.png'),
              name: "If Elif and Else Statements in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "09:06",
            },
            {
              id: "7-2",
              src: require('../static/cluding-type1.png'),
              name: "For Loops in Python",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: true,
              time: "18:17",
            },
            {
              id: "7-3",
              src: require('../static/cluding-type1.png'),
              name: "Comparison Operators Quiz",
              subName: "In this section of the Python course, learn how to use Python and control flow to add logic to your Python scripts!",
              underline: false,
              time: "10:35",
            },
          ],
        },
      ],
      openSubNames: [],
      openChildrenIds: [1]
    };
  },
  mounted() {
    this.$nextTick(() => {
      window.onscroll = () => {
        const scrollTop =
          document.documentElement.scrollTop || document.body.scrollTop;
        if (scrollTop > 400) {
          this.sideShow = true;
        } else {
          this.sideShow = false;
        }
      };
    });
  },
  methods: {
    onOpenCollapse() {
      this.collapseShow = true;
      this.openChildrenIds = this.contentList.map(r => r.id);
    },
    onCloseCollapse() {
      this.collapseShow = false;
      this.openChildrenIds = [];
    },
    onSubNameChange(name) {
      if (this.openSubNames.includes(name)) {
        this.openSubNames.splice(this.openSubNames.indexOf(name), 1)
      } else {
        this.openSubNames.push(name)
      }
    },
    onChildrenChange(id) {
      if (this.openChildrenIds.includes(id)) {
        this.openChildrenIds.splice(this.openChildrenIds.indexOf(id), 1)
      } else {
        this.openChildrenIds.push(id)
      }
    }
  },
};
</script>
<style src="./index.css"></style>

