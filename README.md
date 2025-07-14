# 项目展示

欢迎来到我的个人博客！这里是我分享技术、生活和交易心得的地方。

## 交易账户展示

<div id="ctrader-plugin-root" style="width: 1500px; height: 3500px; position: relative; border: 1px solid #ddd; margin: 20px 0;"></div>
<script id="init" type="text/javascript" defer src="https://ct.spotware.com/widget.js"></script>
<script type="text/javascript">
    const script = document.getElementById('init');
    
    script.onload = () => {
        putInitScript('runPlugin');
        runPlugin('ctrader-plugin-root', {"route":"/esp/103543/?lang=zh&theme=dark","appConfig":{"strategy":{"showStrategyPromotion":true}}});
    };
</script>

