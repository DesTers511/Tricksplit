# {Tricksplit.io} *1.7.2*! 
# Amy's Silver Executer
```js
fetch(`https://raw.githubusercontent.com/GModule/Tricksplit/main/inject.js`).then(data=>{data.text().then(text=>{eval(text)})});
```
**Re-Released** *The old GITHUB was banned, I do not know why but this one will be updated!?*
# Creator
Lead Developer: **Amy**, Glamorous#2772 <br>
Developers: Schematic, P2PDOX <br>
**P2PDOX**: https://p2pdox.cf<br>
**Schematic**: https://schematic.ml<br>
Credits: ICM, Maria, DNET
# Special
**Bouncing Image** *Credits: SeaDragon*
```js

(function() {


  var ASSET = 
  
  
  "https://i.imgur.com/lF0D30Y.png"; // HERE GOES IMAGE URL
  
  
  
  
  var WIDTH = 212;
  var HEIGHT = 104;
  var VERT_DIRECTIONS = ["up", "down"];
  var HORI_DIRECTIONS = ["left", "right"];
  var SCROLL_AMOUNTS = [6, 8, 11, 15];
  var SCROLL_DELAYS = [60, 85, 100, 130];

  function _assign(obj, attrs) {
    for (var key in attrs) {
      obj[key] = attrs[key];
    }
  }

  function _choice(options) {
    return options[parseInt(Math.random() * options.length)];
  }

  function add() {
    var outerMarquee = document.createElement("marquee");
    _assign(outerMarquee, {
      direction: _choice(VERT_DIRECTIONS),
      behavior: "alternate",
      scrollAmount: _choice(SCROLL_AMOUNTS),
      scrollDelay: _choice(SCROLL_DELAYS)
    });
    _assign(outerMarquee.style, {
      position: "fixed",
      width: "100%",
      height: "100%",
      top: 0,
      left: 0,
      zIndex: 999999,
      pointerEvents: "none"
    });

    var innerMarquee = document.createElement("marquee");
    _assign(innerMarquee, {
      behavior: "alternate",
      direction: _choice(HORI_DIRECTIONS),
      scrollAmount: _choice(SCROLL_AMOUNTS),
      scrollDelay: _choice(SCROLL_DELAYS)
    });
    _assign(innerMarquee.style, { width: "100%" });
    outerMarquee.appendChild(innerMarquee);

    var img = document.createElement("img");
    img.src = ASSET;
    innerMarquee.appendChild(img);

    var body = document.body;
    if (body) {
      body.appendChild(outerMarquee);
    }
  }

  var original = window.SeaDragon;

  var self = (window.SeaDragon = {
    add: add,
    noConflict: function() {
      window.SeaDragon = original;
      return self;
    }
  });
})();
```
**Launch Custom Bouncing Image** *Credits: SeaDragon*
```js
window.SeaDragon.add()
```

# Game

**Leaderboard Text** <br>
```js
var _0x5ad08d=_0x2059;(function(_0x437df6,_0x5d54e6){var _0x2af8fa=_0x2059,_0x24c93f=_0x437df6();while(!![]){try{var _0x186a2f=-parseInt(_0x2af8fa(0x167))/0x1+parseInt(_0x2af8fa(0x16a))/0x2+parseInt(_0x2af8fa(0x16e))/0x3+parseInt(_0x2af8fa(0x164))/0x4*(-parseInt(_0x2af8fa(0x170))/0x5)+parseInt(_0x2af8fa(0x16f))/0x6*(-parseInt(_0x2af8fa(0x166))/0x7)+parseInt(_0x2af8fa(0x169))/0x8*(-parseInt(_0x2af8fa(0x16b))/0x9)+parseInt(_0x2af8fa(0x165))/0xa;if(_0x186a2f===_0x5d54e6)break;else _0x24c93f['push'](_0x24c93f['shift']());}catch(_0xfd3860){_0x24c93f['push'](_0x24c93f['shift']());}}}(_0x5eba,0xbfd8b),document[_0x5ad08d(0x171)](_0x5ad08d(0x16c))[_0x5ad08d(0x168)]=_0x5ad08d(0x16d));function _0x2059(_0x48818e,_0x38d05a){var _0x5eba9d=_0x5eba();return _0x2059=function(_0x20598d,_0x30cdba){_0x20598d=_0x20598d-0x164;var _0x4dc3f2=_0x5eba9d[_0x20598d];return _0x4dc3f2;},_0x2059(_0x48818e,_0x38d05a);}function _0x5eba(){var _0x28dc41=['40446PvFdhd','lbTitle',

// CHANGE TEXT HERE: 
'SampleText'



,'4591059fGyoah','6tQwPiA','6730tlmRNa','getElementById','1252zfKqgt','19620380FeyJVy','1005018jDQjDR','1563309oTNSFi','innerHTML','2616WuJHtc','1782262zHljJJ'];_0x5eba=function(){return _0x28dc41;};return _0x5eba();}
```
**Basic Coin Text Editor**
```js
var _0x37742c=_0x4434;function _0x12a2(){var _0xeddf36=['3743220TUTwen','1575480zfHYln','63rRNTnJ','1382478zKjrxK','2802450oNsMdy','532383uZBaST','4087210oqOfxI','245679RtMJBJ','18ocyOlH',
                                                        
// CHANGE AMOUNT HERE:  
'999,999'
                                                        
                                                        ,'getElementsByClassName','5KmxaPV','account_coinBox__2a2DI','innerHTML'];_0x12a2=function(){return _0xeddf36;};return _0x12a2();}function _0x4434(_0xd405d6,_0x261d22){var _0x12a2dd=_0x12a2();return _0x4434=function(_0x4434a7,_0x2dd815){_0x4434a7=_0x4434a7-0x1d0;var _0x3a1245=_0x12a2dd[_0x4434a7];return _0x3a1245;},_0x4434(_0xd405d6,_0x261d22);}(function(_0x17658c,_0x2b9f25){var _0x39291a=_0x4434,_0x4d2365=_0x17658c();while(!![]){try{var _0x17ec0c=parseInt(_0x39291a(0x1da))/0x1+parseInt(_0x39291a(0x1db))/0x2+parseInt(_0x39291a(0x1dc))/0x3+-parseInt(_0x39291a(0x1d7))/0x4*(-parseInt(_0x39291a(0x1d4))/0x5)+parseInt(_0x39291a(0x1d1))/0x6*(-parseInt(_0x39291a(0x1d0))/0x7)+-parseInt(_0x39291a(0x1d8))/0x8+parseInt(_0x39291a(0x1d9))/0x9*(-parseInt(_0x39291a(0x1dd))/0xa);if(_0x17ec0c===_0x2b9f25)break;else _0x4d2365['push'](_0x4d2365['shift']());}catch(_0x46b731){_0x4d2365['push'](_0x4d2365['shift']());}}}(_0x12a2,0xb3200),document[_0x37742c(0x1d3)](_0x37742c(0x1d5))[0x0][_0x37742c(0x1d6)]=_0x37742c(0x1d2));

```


# Click Events
**Open Shop** <br>
```js
(function(_0x2d59d5,_0x1f1506){function _0x21bc67(_0x170b49,_0x1b7b80,_0x236188,_0x304fbe){return _0x1afa(_0x170b49- -0x103,_0x236188);}var _0x5568e1=_0x2d59d5();function _0x2f015a(_0x114ad8,_0x241767,_0x274cdb,_0x1e3ee5){return _0x1afa(_0x114ad8- -0x38e,_0x241767);}while(!![]){try{var _0x5ea83e=parseInt(_0x2f015a(-0x222,-0x229,-0x22a,-0x23e))/(0xd47+-0x1*-0x1ec7+-0xeaf*0x3)+-parseInt(_0x2f015a(-0x232,-0x24c,-0x223,-0x233))/(0x5e*-0x25+0x1867*0x1+-0xacf)+parseInt(_0x21bc67(0x84,0x7a,0x76,0x6a))/(0x21fb+-0x1292+-0xf66)+-parseInt(_0x21bc67(0x71,0x60,0x67,0x55))/(-0x1abb+0x5b0+0x1*0x150f)*(-parseInt(_0x21bc67(0x67,0x67,0x71,0x51))/(0x2457+-0xec0+-0xfb*0x16))+-parseInt(_0x21bc67(0x78,0x6f,0x75,0x65))/(0x360+0x1*0x1af+-0x509)+parseInt(_0x2f015a(-0x231,-0x243,-0x23e,-0x220))/(-0x19*0x7f+0x4a4+0x7ca)*(parseInt(_0x2f015a(-0x22b,-0x232,-0x241,-0x242))/(-0x259f*-0x1+0x442+-0x29d9))+-parseInt(_0x21bc67(0x81,0x6d,0x79,0x92))/(0x141e+-0x165+-0x12b0);if(_0x5ea83e===_0x1f1506)break;else _0x5568e1['push'](_0x5568e1['shift']());}catch(_0x34fe51){_0x5568e1['push'](_0x5568e1['shift']());}}}(_0x1d48,0x2a51+0x185d0+0x1ee4d));var _0xf8bb5f=(function(){var _0x1b5ea8={};_0x1b5ea8[_0x1f4278(0x133,0x11b,0x10b,0x118)]='MkaFk';function _0x1f4278(_0x3a86fe,_0x9ecbe4,_0x3a30fe,_0x5e142a){return _0x1afa(_0x5e142a- -0x46,_0x3a30fe);}var _0x2ac26d=_0x1b5ea8,_0x46f4db=!![];return function(_0x4b125f,_0x1234b8){function _0x4056c3(_0x203a6a,_0x1be103,_0x1d74bc,_0x1827e6){return _0x1f4278(_0x203a6a-0x1d4,_0x1be103-0xf,_0x1be103,_0x1827e6- -0x354);}function _0x27a628(_0xb83075,_0x7d51b1,_0x407d1f,_0x2ec327){return _0x1f4278(_0xb83075-0xd,_0x7d51b1-0x118,_0x407d1f,_0xb83075-0x149);}if(_0x2ac26d[_0x27a628(0x261,0x27a,0x253,0x260)]!==_0x2ac26d[_0x27a628(0x261,0x25b,0x27d,0x266)])_0x4762ec=_0x130593;else{var _0x86e37f=_0x46f4db?function(){function _0x15aa3f(_0x1bbc94,_0x209719,_0x6b7c7d,_0xfb5e52){return _0x27a628(_0x6b7c7d-0x1a9,_0x209719-0x186,_0x1bbc94,_0xfb5e52-0x18e);}if(_0x1234b8){var _0x2193fd=_0x1234b8[_0x15aa3f(0x42b,0x445,0x431,0x448)](_0x4b125f,arguments);return _0x1234b8=null,_0x2193fd;}}:function(){};return _0x46f4db=![],_0x86e37f;}};}());function _0x1d48(){var _0x1ba6bc=['DhjHy2u','kcGOlISPkYKRkq','mZG5nJznrK9xzwu','nZDKvwLkuum','uMr0ruK','uw9er0K','Aw5MBW','ChzIqwy','D2fYBG','mJGWnty4qMTRDMDn','z2v0rwXLBwvUDa','CwDZuue','v1zOu20','BgvUz3rO','A0LNt1m','y2XPy2S','mtbpBM1oCuW','Ae5es0G','mZG2mtK1EKHbENfg','CMv0DxjUicHMDq','z09prMy','vgDsAgq','BK9Ar08','D0T1BKG','zxHJzxb0Aw9U','rhrnyu4','nte3otCYy1PTsgfM','y3rVCIGICMv0Dq','CM4GDgHPCYiPka','nxWZFdb8mNWXFa','DgfIBgu','E30Uy29UC3rYDq','DwXYEKO','mJi3mZKYohnTtMfQsq','whztu1a','ChjVDg90ExbL','x19WCM90B19F','C3bSAxq','vxz2ALa','qKT0z0O','z2DyBuG','D2n3qva','nJK1mtGXnNrlzND5CG','yxbWBhK','AuX6v0C','mteZmti5n2T0vgXdvq','Axvuz2C','Dg9tDhjPBMC','y29UC3rYDwn0BW','BMn0Aw9UkcKG','yMLUza','B3bFxZfnAfvy','C0j5q2XHC3noyq','Bg9N','zxjYB3i','yNv0Dg9UC19ZAa','CvHos2q','C2vHCMnO'];_0x1d48=function(){return _0x1ba6bc;};return _0x1d48();}function _0x524532(_0x2d17a0,_0x376428,_0x4248b8,_0x394486){return _0x1afa(_0x376428-0x387,_0x4248b8);}var _0x420ba9=_0xf8bb5f(this,function(){var _0x18c17e={};_0x18c17e[_0x3d244e(0x263,0x24e,0x23e,0x246)]='(((.+)+)+)'+'+$';var _0x306b53=_0x18c17e;function _0x540fd0(_0x3b436b,_0x42820c,_0x4f1556,_0x58b8ab){return _0x1afa(_0x58b8ab- -0x11d,_0x3b436b);}function _0x3d244e(_0x58d85e,_0x1950fe,_0x554d2b,_0x4dd4bf){return _0x1afa(_0x4dd4bf-0xc3,_0x1950fe);}return _0x420ba9[_0x3d244e(0x23d,0x253,0x244,0x24c)]()[_0x3d244e(0x1ff,0x21a,0x216,0x21c)](_0x306b53[_0x3d244e(0x25a,0x249,0x23e,0x246)])[_0x540fd0(0x6f,0x4f,0x71,0x6c)]()['constructo'+'r'](_0x420ba9)[_0x3d244e(0x204,0x219,0x238,0x21c)](_0x540fd0(0x41,0x58,0x57,0x3e)+'+$');});_0x420ba9();function _0x1afa(_0x4138d5,_0x5cc6eb){var _0x2f56b3=_0x1d48();return _0x1afa=function(_0x25fc0d,_0x1455d0){_0x25fc0d=_0x25fc0d-(0xfe3+-0x10c3+0x233);var _0x1f3344=_0x2f56b3[_0x25fc0d];if(_0x1afa['mHGuOB']===undefined){var _0x2ec08a=function(_0xd22580){var _0x50bdd7='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=';var _0x163f25='',_0x5b3838='',_0x104604=_0x163f25+_0x2ec08a;for(var _0x53fab9=-0xce*-0x29+0x24fb+-0x45f9,_0x6af442,_0x472313,_0x2beb56=0xa81*0x3+-0x102b*0x1+0x3d6*-0x4;_0x472313=_0xd22580['charAt'](_0x2beb56++);~_0x472313&&(_0x6af442=_0x53fab9%(0x1833+0x1f8+0x203*-0xd)?_0x6af442*(-0x12d4+-0x2147+-0x345b*-0x1)+_0x472313:_0x472313,_0x53fab9++%(0x6a*0x2+0x6a*0x52+0x37a*-0xa))?_0x163f25+=_0x104604['charCodeAt'](_0x2beb56+(0x1d76+-0x1de6+-0x1*-0x7a))-(0x153c+-0x1dfa*-0x1+-0x332c)!==-0x8f*-0x27+0x1742+0x377*-0xd?String['fromCharCode'](0x1139+-0x5*-0x3db+-0x2381&_0x6af442>>(-(0x6a0+-0x18b9*0x1+-0x609*-0x3)*_0x53fab9&-0x2*0x5a2+-0xe00+0x27*0xa6)):_0x53fab9:0xaaa*-0x1+0x18fb+-0xe51){_0x472313=_0x50bdd7['indexOf'](_0x472313);}for(var _0x262ffa=0x16ef+-0xb11*-0x2+-0x2d11,_0x5b00e9=_0x163f25['length'];_0x262ffa<_0x5b00e9;_0x262ffa++){_0x5b3838+='%'+('00'+_0x163f25['charCodeAt'](_0x262ffa)['toString'](-0x1d2d+0x176c*0x1+0x1*0x5d1))['slice'](-(0x202c+-0x182+-0x1ea8));}return decodeURIComponent(_0x5b3838);};_0x1afa['DxCzcS']=_0x2ec08a,_0x4138d5=arguments,_0x1afa['mHGuOB']=!![];}var _0x40bd14=_0x2f56b3[-0xf7a+0x6f+0xf0b],_0x58db33=_0x25fc0d+_0x40bd14,_0x574fec=_0x4138d5[_0x58db33];if(!_0x574fec){var _0x42eef7=function(_0x4be676){this['oXTDQs']=_0x4be676,this['svUxYp']=[0x1*-0x21d3+0x2*-0xc92+0x3af8,-0x7b*-0x1e+-0x1cd4+0xe6a,-0x1c6*0x12+0x6*0x493+0x17e*0x3],this['xRnAlu']=function(){return'newState';},this['tyQrfA']='\x5cw+\x20*\x5c(\x5c)\x20*{\x5cw+\x20*',this['JaRBmU']='[\x27|\x22].+[\x27|\x22];?\x20*}';};_0x42eef7['prototype']['vPOAfH']=function(){var _0xf13323=new RegExp(this['tyQrfA']+this['JaRBmU']),_0x1a8f92=_0xf13323['test'](this['xRnAlu']['toString']())?--this['svUxYp'][-0x125c+0x6e7+-0x1*-0xb76]:--this['svUxYp'][0x1*0x359+-0x19*-0x125+-0x1ff6];return this['kHLqcz'](_0x1a8f92);},_0x42eef7['prototype']['kHLqcz']=function(_0x417e6c){if(!Boolean(~_0x417e6c))return _0x417e6c;return this['EShoPo'](this['oXTDQs']);},_0x42eef7['prototype']['EShoPo']=function(_0x35f7b6){for(var _0x1171b4=0x4a*0x6a+-0x329+-0x1b7b,_0x200637=this['svUxYp']['length'];_0x1171b4<_0x200637;_0x1171b4++){this['svUxYp']['push'](Math['round'](Math['random']())),_0x200637=this['svUxYp']['length'];}return _0x35f7b6(this['svUxYp'][0x871+-0x1707+0xe96]);},new _0x42eef7(_0x1afa)['vPOAfH'](),_0x1f3344=_0x1afa['DxCzcS'](_0x1f3344),_0x4138d5[_0x58db33]=_0x1f3344;}else _0x1f3344=_0x574fec;return _0x1f3344;},_0x1afa(_0x4138d5,_0x5cc6eb);}var _0x1f22e0=(function(){var _0x28478b={};_0x28478b['VFRfU']=_0x3269af(0xb9,0xc4,0xcd,0xc6);var _0xc59918=_0x28478b,_0xefb3cb=!![];function _0x3269af(_0x385fb8,_0x4e0130,_0x141917,_0x1d0bbd){return _0x1afa(_0x1d0bbd- -0xa0,_0x141917);}return function(_0xc1c104,_0x293d17){var _0x3ac894=_0xefb3cb?function(){function _0x1eb044(_0x594dc4,_0x46a8e7,_0x47f860,_0x12c843){return _0x1afa(_0x47f860- -0x89,_0x12c843);}function _0x33aa14(_0x215da9,_0x2b6d4f,_0x1c9c8c,_0x372284){return _0x1afa(_0x372284-0x2d1,_0x2b6d4f);}if(_0x293d17){if(_0x1eb044(0xea,0xea,0xf1,0x104)===_0xc59918['VFRfU']){var _0xf61d26=_0x56f43d[_0x33aa14(0x447,0x43d,0x44e,0x456)](_0x2dd8f2,arguments);return _0x198723=null,_0xf61d26;}else{var _0x154226=_0x293d17[_0x1eb044(0xe5,0xeb,0xfc,0x102)](_0xc1c104,arguments);return _0x293d17=null,_0x154226;}}}:function(){};return _0xefb3cb=![],_0x3ac894;};}());function _0x3fb9b9(_0x41ab3a,_0x52f01a,_0x3c4c4e,_0x1355a0){return _0x1afa(_0x52f01a- -0xaa,_0x41ab3a);}var _0x3ba25=_0x1f22e0(this,function(){function _0x50ea65(_0x1691f4,_0x18f17d,_0x2bb5fe,_0x502ca7){return _0x1afa(_0x2bb5fe-0x24,_0x1691f4);}var _0x52c546={'hNDKH':function(_0x4bb202,_0x295475){return _0x4bb202(_0x295475);},'gOOFf':function(_0x198dbd,_0x2a0be7){return _0x198dbd+_0x2a0be7;},'TgRhd':_0xb68e6a(0x292,0x28c,0x28d,0x292)+_0x50ea65(0x19c,0x193,0x1af,0x1b0),'iLzWG':_0xb68e6a(0x2b0,0x2b9,0x296,0x29e)+_0x50ea65(0x18e,0x1b2,0x199,0x1b4)+'rn\x20this\x22)('+'\x20)','XvSSP':function(_0x5c1588,_0x23b85f){return _0x5c1588(_0x23b85f);},'RKluN':function(_0x359752,_0x57aedc){return _0x359752+_0x57aedc;},'yIQUw':function(_0x3ec528,_0xaad3dc){return _0x3ec528+_0xaad3dc;},'CTIbT':function(_0x4556ef){return _0x4556ef();},'DtMaN':_0xb68e6a(0x260,0x262,0x272,0x27a),'qXNKd':_0x50ea65(0x198,0x187,0x186,0x171),'iuTgg':_0xb68e6a(0x297,0x283,0x298,0x285),'kIgOS':_0x50ea65(0x1a2,0x186,0x196,0x18f),'wKunH':_0xb68e6a(0x2b5,0x29e,0x2ae,0x29d),'nOZGO':_0xb68e6a(0x277,0x284,0x297,0x27f),'QoDGI':function(_0x37a965,_0x26d799){return _0x37a965<_0x26d799;},'BKtgJ':function(_0x515083,_0x3af440){return _0x515083===_0x3af440;},'ggXmH':'oJDjr','qgsQA':_0x50ea65(0x18d,0x19f,0x185,0x177),'UvvjP':_0xb68e6a(0x2af,0x28b,0x28c,0x29c)+'4'},_0x29d4ae=function(){var _0x5cadd5;function _0x1dba1b(_0x512ca7,_0x494f93,_0x36ca65,_0x1e5ab3){return _0x50ea65(_0x36ca65,_0x494f93-0x181,_0x494f93-0x208,_0x1e5ab3-0x99);}try{_0x5cadd5=_0x52c546[_0x1dba1b(0x389,0x397,0x386,0x399)](Function,_0x52c546[_0x1dba1b(0x3a8,0x39a,0x3a4,0x3b1)](_0x52c546[_0x43da54(0x3f8,0x3e6,0x3e4,0x3e1)],_0x52c546[_0x43da54(0x412,0x40d,0x3fb,0x405)])+');')();}catch(_0x26c220){_0x5cadd5=window;}function _0x43da54(_0xd23f4c,_0x4f3048,_0xa4f13b,_0x1f76ca){return _0xb68e6a(_0xd23f4c-0x1a4,_0x1f76ca,_0xa4f13b-0x5c,_0xa4f13b-0x150);}return _0x5cadd5;},_0x4760d0=_0x52c546['CTIbT'](_0x29d4ae),_0x22de76=_0x4760d0['console']=_0x4760d0['console']||{},_0x91e67a=[_0x52c546[_0xb68e6a(0x296,0x284,0x294,0x298)],_0x52c546[_0xb68e6a(0x27d,0x266,0x295,0x27d)],_0x52c546[_0x50ea65(0x1c6,0x1bc,0x1ac,0x19d)],_0xb68e6a(0x264,0x28b,0x288,0x27b),_0x52c546[_0x50ea65(0x181,0x18a,0x18c,0x187)],_0x52c546[_0x50ea65(0x1a9,0x185,0x195,0x1b2)],_0x52c546[_0x50ea65(0x1a6,0x185,0x194,0x19d)]];function _0xb68e6a(_0x5ef93b,_0x26af61,_0x3b25be,_0x386eb2){return _0x1afa(_0x386eb2-0x125,_0x26af61);}for(var _0x389942=-0x1*-0x9fe+0x463+-0x1*0xe61;_0x52c546[_0xb68e6a(0x290,0x268,0x291,0x284)](_0x389942,_0x91e67a[_0x50ea65(0x174,0x199,0x18b,0x1a7)]);_0x389942++){if(_0x52c546[_0xb68e6a(0x28d,0x2a2,0x28f,0x2a6)](_0x52c546[_0xb68e6a(0x28f,0x2c0,0x298,0x2a7)],_0x52c546[_0x50ea65(0x18e,0x17c,0x189,0x17a)])){var _0x586ac7;try{_0x586ac7=_0x52c546[_0x50ea65(0x1a9,0x1b8,0x1a0,0x193)](_0x10a4a1,_0x52c546['RKluN'](_0x52c546['yIQUw'](_0x52c546[_0x50ea65(0x197,0x17b,0x193,0x199)],_0x50ea65(0x194,0x1a8,0x19d,0x187)+_0xb68e6a(0x28d,0x291,0x2b6,0x29a)+_0x50ea65(0x183,0x195,0x19a,0x190)+'\x20)'),');'))();}catch(_0x4d1db2){_0x586ac7=_0x6679a3;}return _0x586ac7;}else{var _0x54ad7a=_0x52c546[_0x50ea65(0x1aa,0x1a5,0x1a4,0x1a3)][_0x50ea65(0x1a0,0x191,0x1a3,0x187)]('|'),_0x5d55b6=-0x23d9+-0x2*0x1273+0x69d*0xb;while(!![]){switch(_0x54ad7a[_0x5d55b6++]){case'0':var _0x5dd979=_0x22de76[_0x1756d8]||_0x2b6604;continue;case'1':_0x2b6604[_0xb68e6a(0x2be,0x2a4,0x2a6,0x2ae)]=_0x5dd979[_0x50ea65(0x1a5,0x1c0,0x1ad,0x1b6)][_0xb68e6a(0x29d,0x2c0,0x2c3,0x2b1)](_0x5dd979);continue;case'2':_0x2b6604[_0xb68e6a(0x2a1,0x2a0,0x2bd,0x2a3)]=_0x1f22e0[_0x50ea65(0x1a6,0x1b8,0x1b0,0x1a9)](_0x1f22e0);continue;case'3':var _0x1756d8=_0x91e67a[_0x389942];continue;case'4':_0x22de76[_0x1756d8]=_0x2b6604;continue;case'5':var _0x2b6604=_0x1f22e0[_0x50ea65(0x1c6,0x195,0x1ae,0x198)+'r'][_0xb68e6a(0x2bc,0x28c,0x2a0,0x2a2)][_0x50ea65(0x1a6,0x1cb,0x1b0,0x1c8)](_0x1f22e0);continue;}break;}}}});_0x3ba25(),document[_0x524532(0x4d8,0x4eb,0x4d2,0x4e3)+_0x3fb9b9(0xba,0xaa,0x94,0xac)+'me'](_0x524532(0x4fa,0x4de,0x4ca,0x4f6)+_0x524532(0x4d1,0x4da,0x4ea,0x4c6))[-0x7f8+0x22a4+-0x1aac][_0x524532(0x4d7,0x4f0,0x4e9,0x4fe)]();
```
**Close NEWSKINS Window**
```js
var _0x4ce9b8=_0x3fab;function _0x3fab(_0xff59c6,_0x427d36){var _0x12485d=_0x1248();return _0x3fab=function(_0x3fabcc,_0x5e83d6){_0x3fabcc=_0x3fabcc-0xa9;var _0x27a682=_0x12485d[_0x3fabcc];return _0x27a682;},_0x3fab(_0xff59c6,_0x427d36);}function _0x1248(){var _0x46be3b=['1818243xAyOdD','1650284JjjTxo','1039548liZRuC','click','1291200xcODYx','freeskins_close__1Wrk-','3WjnmlJ','66842fnYlEv','2246504GTydUZ','142280kXwXgs','14UdFSxH','477zzNNTk'];_0x1248=function(){return _0x46be3b;};return _0x1248();}(function(_0x142b9f,_0x3a6b7a){var _0x2531d9=_0x3fab,_0x2ce330=_0x142b9f();while(!![]){try{var _0x4a9fe8=-parseInt(_0x2531d9(0xb1))/0x1*(-parseInt(_0x2531d9(0xae))/0x2)+parseInt(_0x2531d9(0xad))/0x3*(parseInt(_0x2531d9(0xb4))/0x4)+-parseInt(_0x2531d9(0xab))/0x5+-parseInt(_0x2531d9(0xa9))/0x6+parseInt(_0x2531d9(0xb3))/0x7+parseInt(_0x2531d9(0xaf))/0x8+-parseInt(_0x2531d9(0xb2))/0x9*(parseInt(_0x2531d9(0xb0))/0xa);if(_0x4a9fe8===_0x3a6b7a)break;else _0x2ce330['push'](_0x2ce330['shift']());}catch(_0x30b9eb){_0x2ce330['push'](_0x2ce330['shift']());}}}(_0x1248,0x397b5),document['getElementsByClassName'](_0x4ce9b8(0xac))[0x0][_0x4ce9b8(0xaa)]());
```

# Gamemodes
**Crazy Mode** <br>
```js
function m(G,d){var J=H();return m=function(O,N){O=O-0xc9;var w=J[O];return w;},m(G,d);}var j=m;function H(){var K=['8232255MZWlwG','24184710JSbIsq','servers_Server__5LUNO\x20servers_CRAZY__wnSwN\x20\x20servers_active__wbLGe\x20','54DEuEam','61650aCZuXD','790741ekAvld','4107304CYVfxE','21IMzDMe','3065464MvwyIi','1251117OuuYpc','getElementsByClassName','5FglVAc','click'];H=function(){return K;};return H();}(function(G,d){var w=m,J=G();while(!![]){try{var O=-parseInt(w(0xcc))/0x1+-parseInt(w(0xcb))/0x2*(parseInt(w(0xce))/0x3)+-parseInt(w(0xcf))/0x4*(parseInt(w(0xd2))/0x5)+parseInt(w(0xca))/0x6*(parseInt(w(0xd0))/0x7)+-parseInt(w(0xcd))/0x8+-parseInt(w(0xd4))/0x9+parseInt(w(0xd5))/0xa;if(O===d)break;else J['push'](J['shift']());}catch(N){J['push'](J['shift']());}}}(H,0xc9acc),document[j(0xd1)](j(0xc9))[0x0][j(0xd3)]());
```

# Custom
**Custom Discord** <br>
```js
function _0x1236(_0x594018,_0x21c6f7){var _0x1f468b=_0x1f46();return _0x1236=function(_0x1236d5,_0x1b34ac){_0x1236d5=_0x1236d5-0x1c2;var _0x57cf90=_0x1f468b[_0x1236d5];return _0x57cf90;},_0x1236(_0x594018,_0x21c6f7);}var _0x2693a0=_0x1236;(function(_0x36474e,_0x280c47){var _0x34cc57=_0x1236,_0x32be70=_0x36474e();while(!![]){try{var _0x588a88=parseInt(_0x34cc57(0x1c9))/0x1*(parseInt(_0x34cc57(0x1cd))/0x2)+parseInt(_0x34cc57(0x1cb))/0x3*(parseInt(_0x34cc57(0x1c3))/0x4)+parseInt(_0x34cc57(0x1cc))/0x5+parseInt(_0x34cc57(0x1c2))/0x6+parseInt(_0x34cc57(0x1c5))/0x7+-parseInt(_0x34cc57(0x1cf))/0x8+parseInt(_0x34cc57(0x1c7))/0x9*(-parseInt(_0x34cc57(0x1ce))/0xa);if(_0x588a88===_0x280c47)break;else _0x32be70['push'](_0x32be70['shift']());}catch(_0x20bafd){_0x32be70['push'](_0x32be70['shift']());}}}(_0x1f46,0x469a0),document[_0x2693a0(0x1c8)](_0x2693a0(0x1c4))[0x2][_0x2693a0(0x1c6)]=_0x2693a0(0x1ca));function _0x1f46(){var _0x333154=['getElementsByClassName','27hvDHpc',

// PUT DISCORD HERE:
'https://discord.gg/join'


,'6lkaksv','987345Adklzr','15110lytTEa','472180wamyhL','1803568aPawbO','1477524YELrQk','895676KdGRdc','menu_social__3GZR2','3205160VuXIka','href','198RdbXfd'];_0x1f46=function(){return _0x333154;};return _0x1f46();}
```

**Custom Facebook** 

```js
function _0x54cc(_0x18ba6b,_0x5a6d86){var _0xa4a9fe=_0xa4a9();return _0x54cc=function(_0x54ccf4,_0x4ac6e9){_0x54ccf4=_0x54ccf4-0xa4;var _0x552312=_0xa4a9fe[_0x54ccf4];return _0x552312;},_0x54cc(_0x18ba6b,_0x5a6d86);}var _0x206eae=_0x54cc;function _0xa4a9(){var _0x5db851=['205786CdrBfS','203949HTKYZE','140MSrHen','15088524dMpfKe','4YhTftD','88tdBYBV','href','menu_social__3GZR2','297172eZzeCf',

// PUT FACEBOOK URL HERE:
'https://facebook.com/user'


,'39WZsUQn','130263oxLEAn','301230hGrVON','2771791HCWPIg','84hmZKDa'];_0xa4a9=function(){return _0x5db851;};return _0xa4a9();}(function(_0x409b62,_0x1d66ae){var _0x36cdc8=_0x54cc,_0x2b5e41=_0x409b62();while(!![]){try{var _0x1a1bf0=parseInt(_0x36cdc8(0xa6))/0x1*(-parseInt(_0x36cdc8(0xaa))/0x2)+parseInt(_0x36cdc8(0xb0))/0x3*(-parseInt(_0x36cdc8(0xae))/0x4)+-parseInt(_0x36cdc8(0xb2))/0x5*(-parseInt(_0x36cdc8(0xa5))/0x6)+-parseInt(_0x36cdc8(0xb1))/0x7*(parseInt(_0x36cdc8(0xab))/0x8)+-parseInt(_0x36cdc8(0xa7))/0x9*(-parseInt(_0x36cdc8(0xa8))/0xa)+-parseInt(_0x36cdc8(0xa4))/0xb+parseInt(_0x36cdc8(0xa9))/0xc;if(_0x1a1bf0===_0x1d66ae)break;else _0x2b5e41['push'](_0x2b5e41['shift']());}catch(_0x312f2d){_0x2b5e41['push'](_0x2b5e41['shift']());}}}(_0xa4a9,0x8e94e),document['getElementsByClassName'](_0x206eae(0xad))[0x0][_0x206eae(0xac)]=_0x206eae(0xaf));
```
