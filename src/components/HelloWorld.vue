<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>已运行项目</h2>
    <ul>
      <li>
        <a
          href="http://baike.cjunqi.com"
          target="_blank"
        >
          641大百科
        </a>
      </li>
      <li>
        <a
          href="http://hotel.cjunqi.com"
          target="_blank"
        >
          天上人间酒店系统
        </a>
      </li>
      <li>
        <a
          href="http://qianxun.cjunqi.com"
          target="_blank"
        >
          千寻摄影比赛
        </a>
      </li>
      <li>
        <a
          href="http://sm15.cjunqi.com"
          target="_blank"
        >
          院运会邀请函
        </a>
      </li>
      <br />
      <li>
        <a
          href="http://wc15.cjunqi.com"
          target="_blank"
        >
          迎新晚会邀请函
        </a>
      </li>
      <li>
        <a
          href="http://logo.cjunqi.com"
          target="_blank"
        >
          logo设计大赛
        </a>
      </li>
      <li>
        <a
          href="http://cjunqi.com:8888/liaomei/liaomeiServer/Login/login.php"
          target="_blank"
        >
          聊魅即时通讯
        </a>
      </li>
      <br />
      <li>
        <a
          href="http://cjunqi.com:8080/VR"
          target="_blank"
        >
          虚拟现实门户网站
        </a>
      </li>
      <li>
        <a
          href="http://cjunqi.com:8080/VR/#/admin"
          target="_blank"
        >
          虚拟现实门户网站管理员
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to cjunqi.com'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
