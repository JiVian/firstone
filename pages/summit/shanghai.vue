<template>
<div class="content">

<div class="index-bgwrap">
    <!--<div w3-include-html="top.html"></div>-->

    <section class="index-bgdd text-center container">
        <div class="index-bg text-center">
            <img src="/images/finwise/llogo.png" alt="" class="clogo-img">
            <div class="foot-p text-center">
                <!-- <a href="http://www.huodongxing.com/go/finwise2017" target="_blank"><span class="corange-btn bz-btn mar-rt15">报名参加</span></a> -->
                <!-- <a href="./appc.html"><span class="corange-btn bz-btn">成为赞助商</span></a> -->
            </div>
        </div>
    </section>
</div>

<!-- 数字显示-->
<section class="A-wrap container c-important bg-white">

    <div>
        <div class="row count-wrap data-item">
            <ul class="swatch-a col-md-1">
                <li class="number"> 2,000+ </li>
                <li class="title">
                   <!-- 参会嘉宾 -->
                    {{ $t('page.chjb13')}}</li>
            </ul>
            <ul class="swatch-b col-md-1">
                <li class="number"> 70+ </li>
                <li class="title"> 
                  <!-- 金融科技 -->
                  {{ $t('SH.adv345')}}  <br>
                  <!-- 意见领袖 -->
                   {{ $t('SH.adv346')}}</li>
            </ul>
            <ul class="swatch-c  col-md-1">
                <li class="number"> 200+ </li>
                <li class="title"> 
                  <!-- 投资机构 -->
                  {{ $t('page.tzjg14')}} </li>
            </ul>
            <ul class="swatch-d col-md-1">
                <li class="number"> 80+ </li>
                <li class="title">
                   <!-- 媒体参与报道  -->
                   {{ $t('page.mtbd15')}}</li>
            </ul>
            <ul class="swatch-e col-md-1">
                <li class="number"> 50+ </li>
                <li class="title"> 
                  <!-- 国内外顶尖 -->
                  {{ $t('page.perproject1')}}    <br>
                  <!-- 区块链项目 -->
                  {{ $t('page.perproject2')}} </li>
            </ul>
        </div>
    </div>
    <!--end list-->

    <!-- 源文件缺失 -->  <!-- 中国上海 -->
    <!-- <div class="ad-fimg">
        <h2 class="ad-h2title">
          {{ $t('SH.address')}} <b class="and-cl">X</b>2017 FINWISE</h2>
    </div> -->


    <div class="contact-wrap">
        <span class="h6-title">
          <!-- 地址 -->
          {{ $t('page.mcaddr')}}
        </span>
        <p class="cm-ct">
          <!-- 中国上海 卓美亚喜马拉雅酒店 -->
          {{ $t('SH.hotel12')}}
        </p>
        <!-- <span class="h6-title">时间</span>
        <p class="cm-ct">2017-7/30-08:30 — 7/31-17:00</p> -->

        <div class="cm-ct">
            <p class="fh-intro fh-top">
              <!-- 2017年7月30日，纷智·全球区块链峰会将在中国·上海举办。此次峰会旨在推动中国科技金融在全球的发展，帮助中国的优秀区块链团队登上世界舞台，向世界展示中国的科技金融力量。此次峰会立足国内金融科技发展，集合全球优秀金融科技及区块链企业，对未来科技金融及区块链技术应用发展，进行技术及项目层面的展望，并响应把上海建设为国际金融中心的规划，让技术创新造就金融科技的新未来。 -->
              {{ $t('SH.prodqwe')}}</p>
            <!-- <p class="fh-intro"> 随着科技金融在全球的飞速发展，区块链技术得到越来越多的重视。</p> -->
            <!-- <p class="fh-intro">此次峰会立足国内金融科技发展，集合全球优秀金融科技及区块链企业，对未来科技金融及区块链技术应用发展，进行技术及项目层面的展望，并响应把上海建设为国际金融中心的规划，让技术创新造就金融科技的新未来。</p> -->
        </div>

    </div>

</section>
<!-- 参会演讲嘉宾（部分） -->
<section class="mar-auto container xh-container guest-item">
    <h2 class="h2-title text-center">
      <!-- 参会演讲嘉宾(部分) -->
      {{ $t('SH.speak23')}}
      </h2>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhaochangpeng.jpg" alt="赵长鹏" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">赵长鹏</p>
                <p class="pl-info">币安CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/liqiyuan.jpg" alt="李启元" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">李启元</p>
                <p class="pl-info">比特币中国 联合创始人&CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/yanglinke.jpg" alt="杨林科" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">杨林科</p>
                <p class="pl-info">比特币中国联合创始人、 ICOCOIN创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/guohongcai.jpg" alt="郭宏才" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">郭宏才</p>
                <p class="pl-info">比特币天使投资人、以太坊初创公司天使投资人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhangshousong.jpg" alt="张寿松" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">张寿松</p>
                <p class="pl-info">比特币交易网CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/dujun.jpg" alt="杜均" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">杜均</p>
                <p class="pl-info">金色财经 CEO</p>
            </div>
        </div>
        
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/xuemanzi.jpg" alt="宫志国" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">薛蛮子</p>
                <p class="pl-info">天使投资人</p>
            </div>
        </div> 
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/wangyuehua.jpg" alt="欧阳文伟" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">王岳华</p>
                <p class="pl-info">德丰杰龙脉创新基金 合伙人</p>
            </div>
        </div>
        
        
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/eric.png" alt="顾颖" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">顾颖</p>
                <p class="pl-info">维优 CEO、元界基金会主席</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/duanxinxing.jpg" alt="段新星" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">段新星</p>
                <p class="pl-info">巴比特 执行总裁</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/sunmingwei.jpg" alt="孙明伟" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">孙明伟</p>
                <p class="pl-info">块讯 创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/wubinhua.jpg" alt="David Moskowitz" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">吴兵华</p>
                <p class="pl-info">UGCHAIN 创始人</p>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/jen.jpg" alt="李明泽" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">李明泽</p>
                <p class="pl-info">ZENGOLD CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhangjie.jpg" alt="张杰" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">张杰</p>
                <p class="pl-info">C链 创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/hughmadden.jpg" alt="Hugh Madden" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Hugh Madden</p>
                <p class="pl-info">openANX 科技总监</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/wangyi.jpg" alt="董长治" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">董长治</p>
                <p class="pl-info">Basic World 联合创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/xugang.jpg" alt="徐刚" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">徐刚</p>
                <p class="pl-info">Cloudchain 创始人&CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/huangsheng.jpg" alt="黄胜" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">黄胜</p>
                <p class="pl-info">流量矿石 创始人&CEO</p>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/shentuchunchun.jpg" alt="申屠春春" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">申屠春春</p>
                <p class="pl-info">银链科技 CEO</p>
            </div>
        </div>  
        
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhuxueqian.jpg" alt="朱学谦" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">朱学谦</p>
                <p class="pl-info">茶链 CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/wangxiaoming.jpg" alt="汪晓明" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">汪晓明</p>
                <p class="pl-info">HPB（芯链）创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/eddytravia.jpg" alt="Eddy Travia" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Eddy Travia</p>
                <p class="pl-info">Coinsilium CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/alexnorta.jpg" alt="Alex Norta" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Alex Norta</p>
                <p class="pl-info">Agrello CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/avivaounap.jpg" alt="Aviva Ounap" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Aviva Ounap</p>
                <p class="pl-info">Openledger CMO</p>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/changxia.jpg" alt="长铗" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">长铗</p>
                <p class="pl-info">巴比特 CEO</p>
            </div>
        </div>  
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/huangweiguo.jpg" alt="黄伟国" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">黄伟国</p>
                <p class="pl-info">知产链IPC 商务总监</p>
            </div>
        </div>  
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhangliaoliao.jpg" alt="张了了" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">张了了</p>
                <p class="pl-info">牛比特创始合伙人、区块链联合发展组织副秘书长</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/yuchen.jpg" alt="孙宇晨" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">孙宇晨</p>
                <p class="pl-info">TRON 创始人兼CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/linlianwei.jpg" alt="凌连伟" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">凌连伟</p>
                <p class="pl-info">游戏链 创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/guyue.jpg" alt="谷岳" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">谷岳</p>
                <p class="pl-info">惠通天下 创始人</p>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/chenhao.jpg" alt="陈浩" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">陈浩</p>
                <p class="pl-info">维优 首席技术官</p>
            </div>
        </div>  
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/jiangyouming.jpg" alt="蒋佑明" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">蒋佑明</p>
                <p class="pl-info">维优 副总裁</p>
            </div>
        </div>  
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/tarmar.jpg" alt="Tarmar" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Tarmar Menteshashvili</p>
                <p class="pl-info">Aimwise Co-founder</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/you.jpg" alt="Riconi You" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Riconi You</p>
                <p class="pl-info">FINWEX 创始人兼CEO, FINWISE 执行主席</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/chenqiannan.jpg" alt="陈倩楠" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Nancy Chen</p>
                <p class="pl-info">ZENAIR CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/ahmend.jpg" alt="Ahmed Al-Balaghi" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Ahmed Al-Balaghi</p>
                <p class="pl-info">复旦区块链协会 联合创始人&主席</p>
            </div>
        </div> 
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhangyinhai.jpg" alt="张银海" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">张银海</p>
                <p class="pl-info">千方基金 发起人</p>
            </div>
        </div>
        
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/liuyongzhe.jpg" alt="刘永哲" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">刘永哲</p>
                <p class="pl-info">Aimwise 联合创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/raymond.jpg" alt="Raymond" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Raymond He</p>
                <p class="pl-info">维优 高级商务经理</p>
            </div>
        </div> 
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/davidmoskowitz.jpg" alt="David Moskowitz" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">David Moskowitz</p>
                <p class="pl-info">Indorse CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/liuzhaoqing.jpg" alt="刘朝清" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">刘朝清</p>
                <p class="pl-info">耦合链CPL智能合约系统 技术总监</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/liuzhongkui.jpg" alt="刘忠奎" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">刘忠奎</p>
                <p class="pl-info">读脉科技 CEO</p>
            </div>
        </div>  
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/linhao.jpg" alt="林灏" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">林灏</p>
                <p class="pl-info">ETchain 创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/yangjianjun.jpg" alt="杨建军" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">杨建军</p>
                <p class="pl-info">比特币国际集团 创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/tomoaki.jpg" alt="tomoaki sato" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">tomoaki sato</p>
                <p class="pl-info">Director of Starbase</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/shangjinjun.jpg" alt="商敬军" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">商敬军</p>
                <p class="pl-info">乾照光电副 董事长</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/linzihao.jpg" alt="凌子豪" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">凌子豪</p>
                <p class="pl-info">比特币中国 产品总负责人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/cuimeng.jpg" alt="崔萌" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">崔萌</p>
                <p class="pl-info">Achain 创始人</p>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/wangzhongming.jpg" alt="王忠鸣" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">王忠鸣</p>
                <p class="pl-info">比特币之家 CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/huzhen.jpg" alt="胡震" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">胡震</p>
                <p class="pl-info">阔悦科技 CTO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhanglinan.jpg" alt="张李楠" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">张李楠</p>
                <p class="pl-info">7宝网 COO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/alexilane.jpg" alt="Alexi Lane" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Alexi Lane</p>
                <p class="pl-info">Everex CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zhudaolin.jpg" alt="朱导麟" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">朱导麟</p>
                <p class="pl-info">比特币中国合规与监管 副总裁</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/zuoyuyao.jpg" alt="左玉瑶" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">左玉瑶</p>
                <p class="pl-info">流量联盟链 COO</p>
            </div>
        </div>  
    </div>  
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/yelu.jpg" alt="耶鲁·瑞首雷尔" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">耶鲁·瑞首雷尔一世</p>
                <p class="pl-info">瑞迈永强联合创始人、董事长及CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/gaoqingzhong.jpg" alt="高庆忠" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">高庆忠</p>
                <p class="pl-info">智能矩阵Atmatrix基金会主席、智能矩阵Atmatrix社区发起人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/ouyangwenwei.jpg" alt="欧阳文伟" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">欧阳文伟</p>
                <p class="pl-info">铂链BOTTOS落地应用首个区块链机器人RIVEXO CEO</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/panpengchen.jpg" alt="潘鹏程" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">潘鹏程</p>
                <p class="pl-info">厚朴万象区块链、云分布网络科技、CPC创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/miklos.jpg" alt="miklos" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Miklos Denkler</p>
                <p class="pl-info">Founder & CEO of Corion</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/xinweilian.jpg" alt="辛卫廉" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">辛卫廉</p>
                <p class="pl-info">春山浦江投资管理中国大区 合伙人</p>
            </div>
        </div> 
    </div>
    <div class="row">
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/gongzhiguo.jpg" alt="宫志国" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">宫志国</p>
                <p class="pl-info">上海福闰源网络科技有限公司董事长、源币网创始人</p>
            </div>
        </div>
        <div class="col-md-2">
            <div>
                <img src="/images/finwise/numakura.jpg" alt="Yu Numakura" class="party-pl">
            </div>
            <div class="foot-p text-left">
                <p class="plname-info">Yu Numakura</p>
                <p class="pl-info">Founder & CEO, mikuga Japan Corporaiton</p>
            </div>
        </div>
    </div>
</section>
<!-- 联合主办 -->
<section class="mar-auto container footer-wrap">

    <h2 class="h2-title text-center">
      <!-- 联合主办 -->
      {{$t('page.organisers')}}</h2>
    <div class="row count-wrap">
        <ul class="swatch-b col-md-2">
            <img src="/images/finwise/logo_BJDO.png" alt="区块链联合发展组织">
        </ul>
        <ul class="swatch-a col-md-2">
            <img src="/images/finwise/logo_8btc.png" alt="巴比特">
        </ul>
        <ul class="swatch-b col-md-2">
            <img src="/images/finwise/logo_icocoin.png" alt="ICOCOIN">
        </ul>
        <ul class="swatch-b col-md-2">
            <img src="/images/finwise/logo_Jin.png" alt="金色财金">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_btc123.jpg" alt="BTC123">
        </ul>
        <ul class="swatch-a col-md-2">
            <img src="/images/finwise/logo_btcfamily.png" alt="比特币之家">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/MVSfoundation.png" alt="元界基金会">
        </ul>
        <ul class="swatch-a col-md-2">
            <img src="/images/finwise/logo_btcchina.png" alt="比特币中国">
        </ul>
        <ul class="swatch-b col-md-2">
            <img src="/images/finwise/logo_sosobtc.png" alt="Sosobtc">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_binance.png" alt="币安">
        </ul>
        
        <ul class="swatch-a col-md-2">
            <img src="/images/finwise/logo_blocknews.png" alt="blocknews">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_kuaixun.png" alt="yoyow">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_aimwise.png" alt="Aimwise">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_bixin.png" alt="币信">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_cchain.png" alt="cchain">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_tea.png" alt="茶链">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_coupling.png" alt="Coupling">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_oax.png" alt="OAX">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_mvs.png" alt="MVS">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_szzc.png" alt="海枫藤">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_zengold.png" alt="zengold">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_zendao.png" alt="zendao">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_zenair.png" alt="zenair">
        </ul>
        <ul class="swatch-a col-md-2">
            <img src="/images/finwise/logo_wechatme.png" alt="币圈早知道">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_cloudchian.png" alt="云链">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_liuliang.png" alt="流量矿石">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_yunbit.png" alt="云分布">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_etcchain.png" alt="泛娱链">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_basicworld.png" alt="Basic World">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_Gong.png" alt="龚清华律所">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_fudan.png" alt="fudan">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_tron.png" alt="Tron">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_sharedfinance.png" alt="共享财经">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_bitcoin86.png" alt="bitcoin86">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_blockchaingame.png" alt="blockchaingame">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_coldlar.png" alt="coldlar">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_exchangeunion.png" alt="exchangeunion">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_ip.png" alt="Ip">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_hbp.png" alt="hbp">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_bottos.png" alt="bottos">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_yinlian.png" alt="yinlian">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_3dchain.png" alt="3dchain">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_llt.png" alt="llt">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_btc9.png" alt="btc9">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_bullbtc.png" alt="bullbtc">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_meiribidu.png" alt="每日币读">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_bitgo.png" alt="bitgo">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_etclab.png" alt="etclab">
        </ul>
    </div>
    <div class="row count-wrap">
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_ebtcbank.png" alt="ebtcbank">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_achain.png" alt="achain">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_7bao.png" alt="7bao">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_atmatrix.png" alt="Atmatrix">
        </ul>
        <ul class="swatch-c  col-md-2">
            <img src="/images/finwise/logo_tuoniao.png" alt="鸵鸟创投">
        </ul>
    </div>


</section>
<!-- 大会精彩瞬间 -->
<div class="moment" ref="moment">
    <h3>{{ $t('page.dhjc1')}}</h3>
    <div class="moment_title">
      <!--大咖风采，演讲现场，精彩圆桌，展会现场  -->
      <div :class="{'title_active': navActive === 0}" @click="navActive = 0">{{ $t('page.jcqb')}}</div>
      <div :class="{'title_active': navActive === 1}" @click="navActive = 1">{{ $t('SH.jczq')}}</div>
      <div :class="{'title_active': navActive === 2}" @click="navActive = 2">{{ $t('SH.ncjj')}}</div>
    </div>
    <div class="moment_all"  v-if="navActive === 0">
      <img  v-for="val in photoLess" :src="val.url" alt="">
      <!-- 加载更多 -->
      <div class="partic_more" @click="more" v-if="photojz !== photo.length">{{ $t('page.jzgd')}}</div>
    </div>
    <div class="moment_all" v-if="navActive === 1">
        <img  v-for="val in photo1" :src="val.url" alt="">
    </div>
    <div class="moment_all"  v-if="navActive === 2">
        <img  v-for="val in photo2" :src="val.url" alt="">
    </div>
   
</div>
<!--mask begin-->
<div class="show_areabox">
    <div class="mask-con">
        <p class="end-act">
          <!-- 报名已经截止 -->
          {{$t('page.res898')}}</p>
        <div class="text-center"><span class="corange-btn bz-btn maskclose">
          <!-- 关闭 -->
          </span></div>
    </div>
    <div class="mask maskclose"></div>
</div>
<!--mask end-->

<div w3-include-html="bottom.html"></div>
<!-- 返回顶部 -->
<scrollTop></scrollTop>
</div>
</template>

<script>
import { mapMutations, mapState, mapGetters } from 'vuex';
import scrollTop from '../../components/goTop'
export default {
    head() {
      return {
        title: this.$t('page.pageTitle')
      }
    },
    layout: "summit",
    components: {
      scrollTop
    },
    computed: {
      ...mapGetters("app", ["isEnglish"]),
    },
    data() {
        return {
            navActive:0,
            photojz:12,
            photo:[],
            photoLess:[]
        }
    },
    async asyncData(ctx){
        console.log(ctx)
        ctx.store.commit("changeUrl", ctx.route.name);
        //精彩瞬间数据
        let photo = await ctx.$axios.get("/api/photo?catetory=3&type=all");
        let photo1 = await ctx.$axios.get("/api/photo?catetory=3&type=20");
        let photo2 = await ctx.$axios.get("/api/photo?catetory=3&type=21");
        return {
            photo: photo.data.data,
            photo1: photo1.data.data,
            photo2: photo2.data.data,
        }
    },
    methods: {
        more() {
            this.photojz = this.photo.length;
            this.photoLess = this.photo.slice(0,this.photojz)
        }
    },
    mounted() {
      this.photoLess = this.photo.slice(0,this.photojz)
    },
}
</script>


<style lang="less" scoped>
@import "~@style/bundle";
@import "~@style/hody-icons";
@import "~@style/xh-style";

.moment{
    width: 1072px;
    margin: 30px auto;
    flex-direction: column;
    h3 {
      font-size: 24px;
      text-align: center;
      font-weight: 700;
    }
    .moment_title{
      display: flex;
      div{
        height:24px;
        line-height: 24px;
        border: 1px solid #E9E9E9;
        border-radius: 15px;
        text-align: center;
        font-family: SourceHanSansCN-Normal;
        font-size: 12px;
        color: #4A556D;
        padding:0 10px;
        margin:20px 14px 10px 14px;
        cursor: pointer;
      }
      .title_active{
        background-color: #2687F9;
        height:24px;
        line-height: 24px;
        border: 1px solid #E9E9E9;
        border-radius: 15px;
        text-align: center;
        font-family: SourceHanSansCN-Normal;
        font-size: 12px;
        color: #fff;
        margin:20px 14px 10px 14px;
        padding:0 10px;
        cursor: pointer;
      }
    }
    .moment_all{
      display:flex;
      flex-wrap:wrap;
      img{
        width: 246px;
        height: 166px;
        margin: 10px;
      }
    }
    .partic_more{
      width:87px;
      height:24px;
      margin: 20px auto;
      border:1px solid #C5CCDB;
      background: url('/images/finwex-summit/HongKong/arrow_down.png') no-repeat;
      background-position:73px 8px;
      background-size:12%;
      font-family: SourceHanSansCN-Normal;
      font-size: 12px;
      color: #4A556D;
      line-height:24px;
      padding-left:10px;
      cursor: pointer;
    }
}
@media screen and (max-width:480px){
.moment {
    width: 100%;
    text-align: center;
    h3 {
      padding-left: 0;
      font-size: 18px;
    }
    h3::after {
      display: none;
      width: 100%;
    }
    .moment_title {
      flex-wrap: wrap;
      margin: 0 auto;
      justify-content: space-between;
      .title_active,
      div {
        margin: 0.1rem;
        padding: 0;
        width: 21%;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
      }
    }
    .moment_all {
      margin: 0 auto;
      padding: 0 0.1rem;
      justify-content: space-between;
      img {
        width: 3.2rem;
        height: 2.4rem;
      }
    }
    .partic_more {
      padding-left: 0;
    }
  }
}
.guest-item .col-md-2{
  height: 200px;

}
</style>