<template>
  <div class="body">
    <div class="top">        
        <div class="navTop container hidden-sm hidden-xs hidden-sm hidden-xs">
            <img class="logo fl" src="../../static/index/images/logo.png" alt="">
            <div class="fr">
                <ul class="nav nav-pills fl leftNav">
                    <li role="presentation">
                        <a href="#jj">产品简介</a>
                    </li>
                    <li role="presentation">
                        <a href="#gn">功能说明</a>
                    </li>
                    <li role="presentation">
                        <a href="#td">产品特点</a>
                    </li>
                    <li role="presentation">
                        <a href="#al">成功案例</a>
                    </li>
                    <li role="presentation">
                        <a href="#we">关于我们</a>
                    </li>
                </ul>
                <ul class="nav nav-pills fr">
                    <li role="presentation" class="active">
                        <a href="#/signIn">企业注册</a>
                    </li>
                    <li role="presentation">
                        <a href="#/login">企业登录</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="navTop dropdown hidden-md hidden-lg navSmall">
          <img class="logo logoSmall" src="../../static/index/images/logo.png" alt="">
          <button class="btn btn-default btn-lg dropdown-toggle fr" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="margin-right:16px;">
              <span class="glyphicon glyphicon-align-justify"></span>
          </button>
          <div class="dropdown-menu row navSmallBox">
              <div class="col-sm-12"><a href="#jj">产品简介</a></div>
              <div class="col-sm-12"><a href="#gn">功能说明</a></div>
              <div class="col-sm-12"><a href="#td">产品特点</a></div>
              <div class="col-sm-12"><a href="#al">成功案例</a></div>
              <div class="col-sm-12"><a href="#we">关于我们</a></div>
          </div>
        </div>
    </div>
    <div class="banners">
        <div class="container bMain hidden-xs hidden-sm">
            <div class="ddd"></div>
            <p>
                <span class="big1">万</span> 亿售电市场17年上半年全国市场化交易电量</p>
            <p>
                <span class="big1">644,200,000,000</span> 千瓦时</p>
            <p>交易电量占电网销售电量比重(即销售电量市场化率)达到
                <span class="big2">21.7%</span>
            </p>
            <p class="pcenter pcenter1">据《电力发展“十三五”规划》预期,2020年全社会用电量6.8万亿千瓦时至7.2万亿千瓦时,年均增长3.6%至4.8%</p>
            <p class="pcenter">这意味着售电市场容量还有巨大的增长空间。</p>
        </div>
        <div class="container hidden-md hidden-lg bMainSmall">
            <div class="ddd"></div>
            <div class="picSmall"></div>
            <p>
                <span class="big1">万</span> 亿售电市场17年上半年全国市场化交易电量</p>
            <p>
                <span class="big1">644,200,000,000</span> 千瓦时</p>
            <p>交易电量占电网销售电量比重(即销售电量市场化率)达到
                <span class="big2">21.7%</span>
            </p>
            <p class="pcenter pcenter1">据《电力发展“十三五”规划》预期,2020年全社会用电量6.8万亿千瓦时至7.2万亿千瓦时,年均增长3.6%至4.8%</p>
            <p class="pcenter">这意味着售电市场容量还有巨大的增长空间。</p>
        </div>
    </div>
    <div id="jj" class="proInfo">
        <div class="container">
            <h3 class="tip">运用大数据，助力售电行业</h3>
            <p>yongege数据运用大数据，软硬件结合为售电公司全业务发展提供一整套解决方案</p>
            <div class="row">
                <div class="col-xs-6 col-sm-6 col-md-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_zdkhd.svg" alt="...">
                        <div class="caption">
                            <h3>test应用程序端</h3>
                            <p>深入终端，电量采集；智能监测能效优化，用电预测、交易管理用大数据为售电公司提供一手解决方案。</p>
                            <p>
                                <a href="http://39.106.106.150/download/windows/yongegetest-win-0.8.0.exe" class="btn btn-primary" role="button">下载客户端</a>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-xs-6 col-sm-6 col-md-3 wxCode">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_xcx.svg" alt="...">
                        <div class="caption">
                            <h3>test用电企业小程序</h3>
                            <p>无需安装，轻量化设计，打开微信就可查看企业用电情况。</p>
                            <p>
                                <a href="javascript:void(0)" class="btn btn-primary" role="button">打开小程序</a>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-xs-6 col-sm-6 col-md-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_fwzx.svg" alt="...">
                        <div class="caption">
                            <h3>test服务中心</h3>
                            <p>无需安装，轻量化设计，打开微信就可查看企业用电情况。</p>
                            <p>
                                <a href="javascript:void(0);" class="btn btn-default disColor" role="button">下载客户端</a>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-xs-6 col-sm-6 col-md-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_CRM.svg" alt="...">
                        <div class="caption">
                            <h3>testCRM</h3>
                            <p>兼容钉钉和企业微信，方便快捷，轻松实现无纸化客户跟踪管理，及时完成对客户让后期服务。</p>
                            <p>
                                <a href="javascript:void(0);" class="btn btn-default disColor" role="button">下载客户端</a>
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="gn" class="proUser">
        <div class="container">
            <h3 class="tip">多种功能，根据需求自由选择</h3>
            <p>yongege数据“test”系列产品融入电力系统及市场理论，运用大数据，结合我们独立设计开发的应用程序及移动产品，为售电公司参与电力市场交易和经营管理提供安全、稳定、优质的信息化保障，同时为签约客户提供便捷高效的售电服务。平台产品涵盖售电管理、购电管理、用电及负荷预测、统计分析、交易结算、客户管理、合约管理等，一站式满足售电公司及购电客户的业务需求。</p>
            <div class="row">
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_sdgl.svg" alt="...">
                        <div class="caption">
                            <h3>售电管理</h3>
                            <p>实现售电分配计划与管理，实现售电公司可持续发展的利润最大化。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_gdgl.svg" alt="...">
                        <div class="caption">
                            <h3>购电管理</h3>
                            <p>实现购电年季月周日计划安排与管理，落实层次化管理，强化售电公司对购电工作的把控力度，控制购电风险。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_ydfhyc.svg" alt="...">
                        <div class="caption">
                            <h3>用电及负荷预测</h3>
                            <p>提供年度、季度、月度、日负荷预测及实时监测，为电力市场竞价及能效服务提供精准的基础参考数据。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_tjfx.svg" alt="...">
                        <div class="caption">
                            <h3>统计分析</h3>
                            <p>提供图形化的数据统计分析功能，捕捉售电公司内外环境中的细微变化。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_jyjs.svg" alt="...">
                        <div class="caption">
                            <h3>交易结算</h3>
                            <p>提供准确、及时、完整的交易结算体系。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_khgl.svg" alt="...">
                        <div class="caption">
                            <h3>客户管理</h3>
                            <p>管理海量客户信息，拓展发电企业客户关系。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_hygl.svg" alt="...">
                        <div class="caption">
                            <h3>合约管理</h3>
                            <p>管理各类与客户签订的合约管理，确保售电公司合约规范化管理，减少合同纠纷。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_fdcxz.svg" alt="...">
                        <div class="caption">
                            <h3>发电侧协作</h3>
                            <p>时刻与发电侧保持紧密协作，掌握上游核心信息。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_clmx.svg" alt="...">
                        <div class="caption">
                            <h3>策略模型</h3>
                            <p>多种策略生产、使用方式，甄选够售电过程各种优势策略模型，增强售电公司技术优势。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_scck.svg" alt="...">
                        <div class="caption">
                            <h3>市场参考</h3>
                            <p>借助test售电运营管理云平台分享test动态收集、整理的市场参考数据，助力售电公司占领信息高地。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_ptgj.svg" alt="...">
                        <div class="caption">
                            <h3>平台工具</h3>
                            <p>实现售电平台中为各功能模块提供公共服务的功能，满足不同业务工作各种需要。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3">
                    <div class="thumbnail">
                        <img src="../../static/index/images/icon_zzfw.svg" alt="...">
                        <div class="caption">
                            <h3>增值服务</h3>
                            <p>根据需要，为售电公司设计开发多种功能强大的增值服务。</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="td" class="proSup">
        <div class="container hidden-sm hidden-xs">
            <h3 class="tip">产品特点</h3>
            <div class="row">
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">1</div>
                        <div class="numright">
                            <h3>免部署</h3>
                            <p>满足售电公司快速开展业务的需求，实现即租即用。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">2</div>
                        <div class="numright">
                            <h3>配置灵活</h3>
                            <p>售电公司可以根据业务需求定制相应基本应用模块和高级应用模块，自由灵活。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">3</div>
                        <div class="numright">
                            <h3>降低成本</h3>
                            <p>管理平台由统一的运维团队负责维护，降低售电公司运维成本。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">4</div>
                        <div class="numright">
                            <h3>数据加密</h3>
                            <p>基于大数据挖掘技术，为售电公司提供更为有效的设计策略、竞价策略、更为精准的负荷预测等关键数据支持。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">5</div>
                        <div class="numright">
                            <h3>多端同步</h3>
                            <p>基于大数据挖掘技术，为售电公司提供更为有效的设计策略、竞价策略、更为精准的负荷预测等关键数据支持。</p>
                        </div>
                    </div>
                </div>         
            </div>
        </div>
        <div class="container proSupSmall hidden-md hidden-lg">
            <h3 class="tip">产品特点</h3>
            <div class="picCom"></div>
            <div class="row">
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">1</div>
                        <div class="numright">
                            <h3>免部署</h3>
                            <p>满足售电公司快速开展业务的需求，实现即租即用。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">2</div>
                        <div class="numright">
                            <h3>配置灵活</h3>
                            <p>售电公司可以根据业务需求定制相应基本应用模块和高级应用模块，自由灵活。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">3</div>
                        <div class="numright">
                            <h3>降低成本</h3>
                            <p>管理平台由统一的运维团队负责维护，降低售电公司运维成本。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">4</div>
                        <div class="numright">
                            <h3>数据加密</h3>
                            <p>基于大数据挖掘技术，为售电公司提供更为有效的设计策略、竞价策略、更为精准的负荷预测等关键数据支持。</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-12">
                    <div class="supbox">
                        <div class="numLeft">5</div>
                        <div class="numright">
                            <h3>多端同步</h3>
                            <p>基于大数据挖掘技术，为售电公司提供更为有效的设计策略、竞价策略、更为精准的负荷预测等关键数据支持。</p>
                        </div>
                    </div>
                </div>         
            </div>
        </div>
    </div>
    <div id="al" class="cooperate">
        <div class="container">
            <h3 class="tip">合作单位</h3>
            <div class="row">
              <div class="col-xs-6 col-sm-4 col-md-3 ">
                  <img src="../../static/index/images/comN1.png" alt="">
              </div>
              <div class="col-xs-6 col-sm-4 col-md-3 ">
                  <img src="../../static/index/images/comN2.png" alt="">
              </div>
              <div class="col-xs-6 col-sm-4 col-md-3 ">
                  <img src="../../static/index/images/comN3.png" alt="">
              </div>
              <div class="col-xs-6 col-sm-4 col-md-3 ">
                  <img src="../../static/index/images/comN4.png" alt="">
              </div>       
            </div>
        </div>
    </div>
    <div id="we" class="footer">
        <div class="container">
            <dl class="foo">
                <dt>关于我们</dt>
                <dd>公司介绍</dd>
                <dd>客户案例</dd>
                <dd>上午合作</dd>
                <dd>联系我们</dd>
            </dl>
            <dl class="foo">
                <dt>产品资料</dt>
                <dd>产品介绍</dd>
                <dd>基础实用手册</dd>
                <dd>管理员手册</dd>
                <dd>官方指南</dd>
            </dl>
            <dl class="foo">
                <dt>服务规则</dt>
                <dd>服务条款</dd>
                <dd>技术支持</dd>
            </dl>
            <dl class="foo">
                <dt>下载test</dt>
                <dd>下载客户端</dd>
                <dd>企业注册test</dd>
            </dl>
        </div>
    </div>
  </div>
</template>

<script>

//引入bootstrap
import 'bootstrap/dist/js/bootstrap.min.js'
import 'bootstrap/dist/css/bootstrap.min.css'

export default {
  name: 'home',
  data () {
    return {
      msg: 'testp',
      value1: 0
    }
  },
  components: {
    alert
  },
  created: function(){
    $(document).ready(function(){
        $('.wxCode').hover(function(){
            $('.wxCode> div').addClass('xiaoChengxu')
        })
        $('.wxCode').mouseleave(function(){
            $('.wxCode> div').removeClass('xiaoChengxu')
        })
    })
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.body{
    background-color: #f2f2f2;
    font-size: 14px;
}
/* 目前适配最小屏 */
.container{
    min-width: 750px;
}
.top {
    border-bottom: 1px solid #f2f2f2;
    background-color: #fff;
}
h3{
  margin-top: 20px;
  margin-bottom: 10px;
}
p{
  margin-bottom: 10px;
}
.fl {
    float: left;
}

.fr {
    float: right;
}

.navTop {
    height: 80px;
}

.logo {
    width: 165px;
    height: 45px;
    margin-top: 20px;
}

.nav>li>a {
    padding: 30px 15px;
}

.nav-pills>li>a {
    border-radius: 0px;
}

.nav-pills>li.active>a,
.nav-pills>li.active>a:hover,
.nav-pills>li.active>a:focus {
    background-color: #0089f0;
}

.navTop a {
    color: black
}

.leftNav {
    margin-right: 20px;
}

.banners {
    width: 100%;
    background-color: #002E50;
}

.bMain {
    background: url(../../static/index/images/map.png) no-repeat;
    background-position: 100% 10px;
    height: 100%;
    background-size: contain;
    color: #fff;
    font-size: 14px;
    padding-top: 120px;
    position: relative;
}

.big1 {
    font-size: 40px;
}

.big2 {
    font-size: 25px;
}

.pcenter {
    text-align: center;
    font-size: 12px;
}

.pcenter1 {
    margin-top: 120px;
}
.proInfo .thumbnail{
    padding-top: 20px;
    height: 270px;            
    position: relative;
}
.btn-primary{
    width: 170px;
    background-color: #0089f0;
}
.caption{
    text-align: center;
}
.caption a{
    position: absolute;
    bottom: 10px;
    margin-left: -85px;
    left: 50%;
}
.caption p{
    color: #999;
}
.disColor{
    background-color: #ccc;
    width: 170px;
    color: #fff
}
.btn-default:hover{
    color: #fff;
    background-color: #ccc;
}
.btn-default:active{
    color: #fff;
    background-color: #ccc;
}
.tip {
    margin-top: 70px;
    font-size: 30px;
    text-align: center;
}
.proInfo .container {
    text-align: center;
}
.container .row{
    margin-top: 40px;
}
h3, .h3{
    font-size: 16px;
    font-weight: 600;
}
/* 功能样式 */
.proUser .caption{
    text-align: left;
}
.proUser .thumbnail{
    height: 120px;
    position: relative;
    padding-left: 70px;
}
.proUser .thumbnail > img, .thumbnail a > img{
    margin: 0;
    position: absolute;
    left: 10px;
    top: 20px;
    width: 60px;
    height: 60px;
}
.proUser .caption h3{
    font-size: 14px;
    margin-top: 0
}
.proUser .caption > p{
    font-size: 12px
}
/* 产品特点 */
.proSup .container .row{
    background: url(../../static/index/images/image.png) no-repeat;
    background-position: 0 50%;
    background-size: 46%;
    
}
.proSup .row{
    padding-left: 50%;
}
.numLeft {
    position: absolute;
    left: 0;
    top: 0;
    width: 40px;
    height: 40px;
    background-color: #0089f0;
    color: #fff;
    font-size: 16px;
    border-radius: 50%;
    text-align: center;
    line-height: 40px;
}
.supbox {
    position: relative;
}
.numright {
    padding-left: 60px;
    font-size: 12px;
}
.numright p{
    color: #888
}
/* 合作单位样式 */
.cooperate {
    background-color: #fff;
    padding-bottom: 50px;
}
.cooperate img{
    width: 120px;
    height: 40px;
    margin: 20px;
}
/* 底部样式 */
.footer{
    background-color: #303036;
    padding-top: 30px;
    font-size: 12px;
}
.foo{
    width: 120px;
    float: left;
    color: #999;
}
.foo dt{
    color: #fff;
    margin-bottom: 15px;
    font-size: 14px;
}
.foo dd{
    margin-bottom: 10px;
}
@-webkit-keyframes glow {
    0% {
        -webkit-box-shadow: 0 0 12px 0px rgba(250, 250, 250, 0.5);
        border-color: rgba(160, 179, 214, 0.5);         
    }
    100% {
        -webkit-box-shadow: 0 0 12px 0px rgba(250, 250, 250, 0.5), 0 0 12px 68px rgba(250, 250, 250, 0.2);
        border-color: rgba(160, 179, 214, 1.0); 
    }
}
.ddd{
    background-color: #fff;
    width: 10px;
    height: 10px;
    position: absolute;
    right: 150px;
    top: 254px;
    border-radius: 50%;
    -webkit-animation-name: glow;
    -webkit-animation-duration: 1s;
    -webkit-animation-iteration-count: infinite;
    -webkit-animation-direction: alternate;
    -webkit-animation-timing-function: ease-in-out;    
}
.xiaoChengxu{
    position: relative;
}
.xiaoChengxu::before, .xiaoChengxu::after {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    position: absolute;
    margin-top: 0;
    top: 0;
    left: 0;
    background-color: rgba(0, 0, 0, 0.6);
    z-index: 11;
}
.xiaoChengxu::after {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    position: absolute;
    margin-top: 0;
    top: 0;
    left: 0;
    background: url(../../static/index/images/wx.jpg) no-repeat;
    background-size: 50%;
    background-position: 50% 50%;
    z-index: 12;
}
.cooperate .row{
    text-align: center;
}
/* 小屏样式 */
.navSmall {
    padding-top: 16px;
    text-align: center;
}
.navSmall .navSmallBox {
    margin-top: 64px;
    top: 0;
    left: 0;
    width: 100%;
}
.navSmall .navSmallBox div {
    height: 30px;
    line-height: 30px;
}
.navSmall .navSmallBox div:hover {
    background-color: #f2f2f2;
}
.navSmall .navSmallBox a {
    display: block;
    width: 100%;
}
.bMainSmall{           
    color: #fff;
    font-size: 14px;
    position: relative;
    text-align: center;
}
.picSmall{
    background: url(../../static/index/images/map.png) no-repeat;
    background-position: 0% 0%;
    height: 615px;
    background-size: contain;
}
.bMainSmall .pcenter1{
    margin-top: 0;
}
.bMainSmall .ddd{
    right: 246px;
    top: 326px;
}
.proSup .proSupSmall .row{
    padding-left: 0;
    background: none;
}
.picCom{
    background: url(../../static/index/images/image.png) no-repeat;
    background-position: 50% 100%;
    background-size: contain;
    width: 100%;
    height: 350px;
    margin-top: 30px;
}
.logoSmall {
    margin: 0 auto;
}
    </style>