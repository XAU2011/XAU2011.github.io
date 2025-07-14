#账户收益

<div id="ctrader-plugin-root" style="width: 100%; height: 3500px; position: relative; border: 1px solid #ddd; margin: 20px 0;"></div>
<script id="init" type="text/javascript" defer src="https://ct.spotware.com/widget.js"></script>
<script type="text/javascript">
    const script = document.getElementById('init');
    
    script.onload = () => {
        putInitScript('runPlugin');
        runPlugin('ctrader-plugin-root', {"route":"/esp/103543/?lang=zh&theme=dark","appConfig":{"strategy":{"showStrategyPromotion":true}}});
    };
</script>

