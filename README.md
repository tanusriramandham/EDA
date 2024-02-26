<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="icon" href="data:image/x-icon;base64,AAABAAEAEBAAAAEACABoBQAAFgAAACgAAAAQAAAAIAAAAAEACAAAAAAAAAEAAAAAAAAAAAAAAAEAAAAAAAAAAAAAPD4/AC0vMADd3+AAWFpbAFlaWwC8vb0AOjw9AERHRwCSlJUAk5SVAJ6fnwD39/cAW1xeAGVnaAC0t7YAgYOEAI2OjgDk5uYA9fX1AFhaXABzdHUA5ubmAG5wcAA6PD4Ax8jIAEVHSAA2ODkAqaqqAPLz8wB7fX0AQ0VGADQ2NwB6e3sAs7W1AJqbnAAjJSYAi4yNAP7+/gDu7+8A7+/vAHZ5eQDf4OAAtbe4ANHR0QBPUFEAwsLCAKioqQCjpKQA/Pz8AO3t7QBrbG0AvcDAAExOTwDJy8oAlpeYAC4wMQDe4OEAkZOTAPr6+gBoamsAWVtcANzc3ABkZmYAKy4vAK6vrwAsLi8A/fz9AJCRkQDe3t8AZmhpANna2gDa2toAYmRkAJGTlADr6+wA9vb2AH6AgABlZmcAYGJiAMjJyQBGSEkAr6+wAIGCgwC3uLgAqKmpANTU1ABSU1QAqqusAEJERQC1trYAlpiYAC8xMQD///8AfX5/AH5+fwBtb3AA8PDwAODh4QB6enoAuLi5ALO0tAA8Pj4A/f39AHt8fQDu7u4Ad3h4AExPUADFxcYA0NDQAMDBwQBOT1AAPkBBAPn7+wDq7OwAeXp7ANvd3QDc3d0AdHZ2AEtNTgBMTU4AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAS1gjNy91XV0MDUItMl1dXSFwGxsbHy5dZEBuPGpdXV0sUx5oNRsbFngiXTkkMl1dXV1dXTtZGzBrXV1dT0RdXV1dXV0dcBsFC11yXTRcQ11dXV1dThsBBzFdFANdGG1dXV1dJRsbeBBdNgBbXQlXXV1dWhsbUzh0XTxjBF1xAkhdKAEbDlVgXSp3XV4PXSlfXVIbHydoK11GVF1QCF0SIF0wGz1dGRdNURxhXWZKU0ldVhsHPl1Fc2UbP10TClJdXV0zG3dHXV1MGhtsXV1dXV1daW8bGzpiJjMbEV1dXV1dXV0nFRsbGwEbG0FdXV1dXV1dXV0GdgcbWTpnXV1dXQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA=" type="image/x-icon" />
        <script> /*! jQuery v3.4.1 | (c) JS Foundation and other contributors | jquery.org/license */
!function(e,t){"use strict";"object"==typeof module&&"object"==typeof module.exports?module.exports=e.document?t(e,!0):function(e){if(!e.document)throw new Error("jQuery requires a window with a document");return t(e)}:t(e)}("undefined"!=typeof window?window:this,function(C,e){"use strict";var t=[],E=C.document,r=Object.getPrototypeOf,s=t.slice,g=t.concat,u=t.push,i=t.indexOf,n={},o=n.toString,v=n.hasOwnProperty,a=v.toString,l=a.call(Object),y={},m=function(e){return"function"==typeof e&&"number"!=typeof e.nodeType},x=function(e){return null!=e&&e===e.window},c={type:!0,src:!0,nonce:!0,noModule:!0};function b(e,t,n){var r,i,o=(n=n||E).createElement("script");if(o.text=e,t)for(r in c)(i=t[r]||t.getAttribute&&t.getAttribute(r))&&o.setAttribute(r,i);n.head.appendChild(o).parentNode.removeChild(o)}function w(e){return null==e?e+"":"object"==typeof e||"function"==typeof e?n[o.call(e)]||"object":typeof e}var f="3.4.1",k=function(e,t){return new k.fn.init(e,t)},p=/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;function d(e){var t=!!e&&"length"in e&&e.length,n=w(e);return!m(e)&&!x(e)&&("array"===n||0===t||"number"==typeof t&&0<t&&t-1 in e)}k.fn=k.prototype={jquery:f,constructor:k,length:0,toArray:function(){return s.call(this)},get:function(e){return null==e?s.call(this):e<0?this[e+this.length]:this[e]},pushStack:function(e){var t=k.merge(this.constructor(),e);return t.prevObject=this,t},each:function(e){return k.each(this,e)},map:function(n){return this.pushStack(k.map(this,function(e,t){return n.call(e,t,e)}))},slice:function(){return this.pushStack(s.apply(this,arguments))},first:function(){return this.eq(0)},last:function(){return this.eq(-1)},eq:function(e){var t=this.length,n=+e+(e<0?t:0);return this.pushStack(0<=n&&n<t?[this[n]]:[])},end:function(){return this.prevObject||this.constructor()},push:u,sort:t.sort,splice:t.splice},k.extend=k.fn.extend=function(){var e,t,n,r,i,o,a=arguments[0]||{},s=1,u=arguments.length,l=!1;for("boolean"==typeof a&&(l=a,a=arguments[s]||{},s++),"object"==typeof a||m(a)||(a={}),s===u&&(a=this,s--);s<u;s++)if(null!=(e=arguments[s]))for(t in e)r=e[t],"__proto__"!==t&&a!==r&&(l&&r&&(k.isPlainObject(r)||(i=Array.isArray(r)))?(n=a[t],o=i&&!Array.isArray(n)?[]:i||k.isPlainObject(n)?n:{},i=!1,a[t]=k.extend(l,o,r)):void 0!==r&&(a[t]=r));return a},k.extend({expando:"jQuery"+(f+Math.random()).replace(/\D/g,""),isReady:!0,error:function(e){throw new Error(e)},noop:function(){},isPlainObject:function(e){var t,n;return!(!e||"[object Object]"!==o.call(e))&&(!(t=r(e))||"function"==typeof(n=v.call(t,"constructor")&&t.constructor)&&a.call(n)===l)},isEmptyObject:function(e){var t;for(t in e)return!1;return!0},globalEval:function(e,t){b(e,{nonce:t&&t.nonce})},each:function(e,t){var n,r=0;if(d(e)){for(n=e.length;r<n;r++)if(!1===t.call(e[r],r,e[r]))break}else for(r in e)if(!1===t.call(e[r],r,e[r]))break;return e},trim:function(e){return null==e?"":(e+"").replace(p,"")},makeArray:function(e,t){var n=t||[];return null!=e&&(d(Object(e))?k.merge(n,"string"==typeof e?[e]:e):u.call(n,e)),n},inArray:function(e,t,n){return null==t?-1:i.call(t,e,n)},merge:function(e,t){for(var n=+t.length,r=0,i=e.length;r<n;r++)e[i++]=t[r];return e.length=i,e},grep:function(e,t,n){for(var r=[],i=0,o=e.length,a=!n;i<o;i++)!t(e[i],i)!==a&&r.push(e[i]);return r},map:function(e,t,n){var r,i,o=0,a=[];if(d(e))for(r=e.length;o<r;o++)null!=(i=t(e[o],o,n))&&a.push(i);else for(o in e)null!=(i=t(e[o],o,n))&&a.push(i);return g.apply([],a)},guid:1,support:y}),"function"==typeof Symbol&&(k.fn[Symbol.iterator]=t[Symbol.iterator]),k.each("Boolean Number String Function Array Date RegExp Object Error Symbol".split(" "),function(e,t){n["[object "+t+"]"]=t.toLowerCase()});var h=function(n){var e,d,b,o,i,h,f,g,w,u,l,T,C,a,E,v,s,c,y,k="sizzle"+1*new Date,m=n.document,S=0,r=0,p=ue(),x=ue(),N=ue(),A=ue(),D=function(e,t){return e===t&&(l=!0),0},j={}.hasOwnProperty,t=[],q=t.pop,L=t.push,H=t.push,O=t.slice,P=function(e,t){for(var n=0,r=e.length;n<r;n++)if(e[n]===t)return n;return-1},R="checked|selected|async|autofocus|autoplay|controls|defer|disabled|hidden|ismap|loop|multiple|open|readonly|required|scoped",M="[\\x20\\t\\r\\n\\f]",I="(?:\\\\.|[\\w-]|[^\0-\\xa0])+",W="\\["+M+"*("+I+")(?:"+M+"*([*^$|!~]?=)"+M+"*(?:'((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\"|("+I+"))|)"+M+"*\\]",$=":("+I+")(?:\\((('((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\")|((?:\\\\.|[^\\\\()[\\]]|"+W+")*)|.*)\\)|)",F=new RegExp(M+"+","g"),B=new RegExp("^"+M+"+|((?:^|[^\\\\])(?:\\\\.)*)"+M+"+$","g"),_=new RegExp("^"+M+"*,"+M+"*"),z=new RegExp("^"+M+"*([>+~]|"+M+")"+M+"*"),U=new RegExp(M+"|>"),X=new RegExp($),V=new RegExp("^"+I+"$"),G={ID:new RegExp("^#("+I+")"),CLASS:new RegExp("^\\.("+I+")"),TAG:new RegExp("^("+I+"|[*])"),ATTR:new RegExp("^"+W),PSEUDO:new RegExp("^"+$),CHILD:new RegExp("^:(only|first|last|nth|nth-last)-(child|of-type)(?:\\("+M+"*(even|odd|(([+-]|)(\\d*)n|)"+M+"*(?:([+-]|)"+M+"*(\\d+)|))"+M+"*\\)|)","i"),bool:new RegExp("^(?:"+R+")$","i"),needsContext:new RegExp("^"+M+"*[>+~]|:(even|odd|eq|gt|lt|nth|first|last)(?:\\("+M+"*((?:-\\d)?\\d*)"+M+"*\\)|)(?=[^-]|$)","i")},Y=/HTML$/i,Q=/^(?:input|select|textarea|button)$/i,J=/^h\d$/i,K=/^[^{]+\{\s*\[native \w/,Z=/^(?:#([\w-]+)|(\w+)|\.([\w-]+))$/,ee=/[+~]/,te=new RegExp("\\\\([\\da-f]{1,6}"+M+"?|("+M+")|.)","ig"),ne=function(e,t,n){var r="0x"+t-65536;return r!=r||n?t:r<0?String.fromCharCode(r+65536):String.fromCharCode(r>>10|55296,1023&r|56320)},re=/([\0-\x1f\x7f]|^-?\d)|^-$|[^\0-\x1f\x7f-\uFFFF\w-]/g,ie=function(e,t){return t?"\0"===e?"\ufffd":e.slice(0,-1)+"\\"+e.charCodeAt(e.length-1).toString(16)+" ":"\\"+e},oe=function(){T()},ae=be(function(e){return!0===e.disabled&&"fieldset"===e.nodeName.toLowerCase()},{dir:"parentNode",next:"legend"});try{H.apply(t=O.call(m.childNodes),m.childNodes),t[m.childNodes.length].nodeType}catch(e){H={apply:t.length?function(e,t){L.apply(e,O.call(t))}:function(e,t){var n=e.length,r=0;while(e[n++]=t[r++]);e.length=n-1}}}function se(t,e,n,r){var i,o,a,s,u,l,c,f=e&&e.ownerDocument,p=e?e.nodeType:9;if(n=n||[],"string"!=typeof t||!t||1!==p&&9!==p&&11!==p)return n;if(!r&&((e?e.ownerDocument||e:m)!==C&&T(e),e=e||C,E)){if(11!==p&&(u=Z.exec(t)))if(i=u[1]){if(9===p){if(!(a=e.getElementById(i)))return n;if(a.id===i)return n.push(a),n}else if(f&&(a=f.getElementById(i))&&y(e,a)&&a.id===i)return n.push(a),n}else{if(u[2])return H.apply(n,e.getElementsByTagName(t)),n;if((i=u[3])&&d.getElementsByClassName&&e.getElementsByClassName)return H.apply(n,e.getElementsByClassName(i)),n}if(d.qsa&&!A[t+" "]&&(!v||!v.test(t))&&(1!==p||"object"!==e.nodeName.toLowerCase())){if(c=t,f=e,1===p&&U.test(t)){(s=e.getAttribute("id"))?s=s.replace(re,ie):e.setAttribute("id",s=k),o=(l=h(t)).length;while(o--)l[o]="#"+s+" "+xe(l[o]);c=l.join(","),f=ee.test(t)&&ye(e.parentNode)||e}try{return H.apply(n,f.querySelectorAll(c)),n}catch(e){A(t,!0)}finally{s===k&&e.removeAttribute("id")}}}return g(t.replace(B,"$1"),e,n,r)}function ue(){var r=[];return function e(t,n){return r.push(t+" ")>b.cacheLength&&delete e[r.shift()],e[t+" "]=n}}function le(e){return e[k]=!0,e}function ce(e){var t=C.createElement("fieldset");try{return!!e(t)}catch(e){return!1}finally{t.parentNode&&t.parentNode.removeChild(t),t=null}}function fe(e,t){var n=e.split("|"),r=n.length;while(r--)b.attrHandle[n[r]]=t}function pe(e,t){var n=t&&e,r=n&&1===e.nodeType&&1===t.nodeType&&e.sourceIndex-t.sourceIndex;if(r)return r;if(n)while(n=n.nextSibling)if(n===t)return-1;return e?1:-1}function de(t){return function(e){return"input"===e.nodeName.toLowerCase()&&e.type===t}}function he(n){return function(e){var t=e.nodeName.toLowerCase();return("input"===t||"button"===t)&&e.type===n}}function ge(t){return function(e){return"form"in e?e.parentNode&&!1===e.disabled?"label"in e?"label"in e.parentNode?e.parentNode.disabled===t:e.disabled===t:e.isDisabled===t||e.isDisabled!==!t&&ae(e)===t:e.disabled===t:"label"in e&&e.disabled===t}}function ve(a){return le(function(o){return o=+o,le(function(e,t){var n,r=a([],e.length,o),i=r.length;while(i--)e[n=r[i]]&&(e[n]=!(t[n]=e[n]))})})}function ye(e){return e&&"undefined"!=typeof e.getElementsByTagName&&e}for(e in d=se.support={},i=se.isXML=function(e){var t=e.namespaceURI,n=(e.ownerDocument||e).documentElement;return!Y.test(t||n&&n.nodeName||"HTML")},T=se.setDocument=function(e){var t,n,r=e?e.ownerDocument||e:m;return r!==C&&9===r.nodeType&&r.documentElement&&(a=(C=r).documentElement,E=!i(C),m!==C&&(n=C.defaultView)&&n.top!==n&&(n.addEventListener?n.addEventListener("unload",oe,!1):n.attachEvent&&n.attachEvent("onunload",oe)),d.attributes=ce(function(e){return e.className="i",!e.getAttribute("className")}),d.getElementsByTagName=ce(function(e){return e.appendChild(C.createComment("")),!e.getElementsByTagName("*").length}),d.getElementsByClassName=K.test(C.getElementsByClassName),d.getById=ce(function(e){return a.appendChild(e).id=k,!C.getElementsByName||!C.getElementsByName(k).length}),d.getById?(b.filter.ID=function(e){var t=e.replace(te,ne);return function(e){return e.getAttribute("id")===t}},b.find.ID=function(e,t){if("undefined"!=typeof t.getElementById&&E){var n=t.getElementById(e);return n?[n]:[]}}):(b.filter.ID=function(e){var n=e.replace(te,ne);return function(e){var t="undefined"!=typeof e.getAttributeNode&&e.getAttributeNode("id");return t&&t.value===n}},b.find.ID=function(e,t){if("undefined"!=typeof t.getElementById&&E){var n,r,i,o=t.getElementById(e);if(o){if((n=o.getAttributeNode("id"))&&n.value===e)return[o];i=t.getElementsByName(e),r=0;while(o=i[r++])if((n=o.getAttributeNode("id"))&&n.value===e)return[o]}return[]}}),b.find.TAG=d.getElementsByTagName?function(e,t){return"undefined"!=typeof t.getElementsByTagName?t.getElementsByTagName(e):d.qsa?t.querySelectorAll(e):void 0}:function(e,t){var n,r=[],i=0,o=t.getElementsByTagName(e);if("*"===e){while(n=o[i++])1===n.nodeType&&r.push(n);return r}return o},b.find.CLASS=d.getElementsByClassName&&function(e,t){if("undefined"!=typeof t.getElementsByClassName&&E)return t.getElementsByClassName(e)},s=[],v=[],(d.qsa=K.test(C.querySelectorAll))&&(ce(function(e){a.appendChild(e).innerHTML="<a id='"+k+"'></a><select id='"+k+"-\r\\' msallowcapture=''><option selected=''></option></select>",e.querySelectorAll("[msallowcapture^='']").length&&v.push("[*^$]="+M+"*(?:''|\"\")"),e.querySelectorAll("[selected]").length||v.push("\\["+M+"*(?:value|"+R+")"),e.querySelectorAll("[id~="+k+"-]").length||v.push("~="),e.querySelectorAll(":checked").length||v.push(":checked"),e.querySelectorAll("a#"+k+"+*").length||v.push(".#.+[+~]")}),ce(function(e){e.innerHTML="<a href='' disabled='disabled'></a><select disabled='disabled'><option/></select>";var t=C.createElement("input");t.setAttribute("type","hidden"),e.appendChild(t).setAttribute("name","D"),e.querySelectorAll("[name=d]").length&&v.push("name"+M+"*[*^$|!~]?="),2!==e.querySelectorAll(":enabled").length&&v.push(":enabled",":disabled"),a.appendChild(e).disabled=!0,2!==e.querySelectorAll(":disabled").length&&v.push(":enabled",":disabled"),e.querySelectorAll("*,:x"),v.push(",.*:")})),(d.matchesSelector=K.test(c=a.matches||a.webkitMatchesSelector||a.mozMatchesSelector||a.oMatchesSelector||a.msMatchesSelector))&&ce(function(e){d.disconnectedMatch=c.call(e,"*"),c.call(e,"[s!='']:x"),s.push("!=",$)}),v=v.length&&new RegExp(v.join("|")),s=s.length&&new RegExp(s.join("|")),t=K.test(a.compareDocumentPosition),y=t||K.test(a.contains)?function(e,t){var n=9===e.nodeType?e.documentElement:e,r=t&&t.parentNode;return e===r||!(!r||1!==r.nodeType||!(n.contains?n.contains(r):e.compareDocumentPosition&&16&e.compareDocumentPosition(r)))}:function(e,t){if(t)while(t=t.parentNode)if(t===e)return!0;return!1},D=t?function(e,t){if(e===t)return l=!0,0;var n=!e.compareDocumentPosition-!t.compareDocumentPosition;return n||(1&(n=(e.ownerDocument||e)===(t.ownerDocument||t)?e.compareDocumentPosition(t):1)||!d.sortDetached&&t.compareDocumentPosition(e)===n?e===C||e.ownerDocument===m&&y(m,e)?-1:t===C||t.ownerDocument===m&&y(m,t)?1:u?P(u,e)-P(u,t):0:4&n?-1:1)}:function(e,t){if(e===t)return l=!0,0;var n,r=0,i=e.parentNode,o=t.parentNode,a=[e],s=[t];if(!i||!o)return e===C?-1:t===C?1:i?-1:o?1:u?P(u,e)-P(u,t):0;if(i===o)return pe(e,t);n=e;while(n=n.parentNode)a.unshift(n);n=t;while(n=n.parentNode)s.unshift(n);while(a[r]===s[r])r++;return r?pe(a[r],s[r]):a[r]===m?-1:s[r]===m?1:0}),C},se.matches=function(e,t){return se(e,null,null,t)},se.matchesSelector=function(e,t){if((e.ownerDocument||e)!==C&&T(e),d.matchesSelector&&E&&!A[t+" "]&&(!s||!s.test(t))&&(!v||!v.test(t)))try{var n=c.call(e,t);if(n||d.disconnectedMatch||e.document&&11!==e.document.nodeType)return n}catch(e){A(t,!0)}return 0<se(t,C,null,[e]).length},se.contains=function(e,t){return(e.ownerDocument||e)!==C&&T(e),y(e,t)},se.attr=function(e,t){(e.ownerDocument||e)!==C&&T(e);var n=b.attrHandle[t.toLowerCase()],r=n&&j.call(b.attrHandle,t.toLowerCase())?n(e,t,!E):void 0;return void 0!==r?r:d.attributes||!E?e.getAttribute(t):(r=e.getAttributeNode(t))&&r.specified?r.value:null},se.escape=function(e){return(e+"").replace(re,ie)},se.error=function(e){throw new Error("Syntax error, unrecognized expression: "+e)},se.uniqueSort=function(e){var t,n=[],r=0,i=0;if(l=!d.detectDuplicates,u=!d.sortStable&&e.slice(0),e.sort(D),l){while(t=e[i++])t===e[i]&&(r=n.push(i));while(r--)e.splice(n[r],1)}return u=null,e},o=se.getText=function(e){var t,n="",r=0,i=e.nodeType;if(i){if(1===i||9===i||11===i){if("string"==typeof e.textContent)return e.textContent;for(e=e.firstChild;e;e=e.nextSibling)n+=o(e)}else if(3===i||4===i)return e.nodeValue}else while(t=e[r++])n+=o(t);return n},(b=se.selectors={cacheLength:50,createPseudo:le,match:G,attrHandle:{},find:{},relative:{">":{dir:"parentNode",first:!0}," ":{dir:"parentNode"},"+":{dir:"previousSibling",first:!0},"~":{dir:"previousSibling"}},preFilter:{ATTR:function(e){return e[1]=e[1].replace(te,ne),e[3]=(e[3]||e[4]||e[5]||"").replace(te,ne),"~="===e[2]&&(e[3]=" "+e[3]+" "),e.slice(0,4)},CHILD:function(e){return e[1]=e[1].toLowerCase(),"nth"===e[1].slice(0,3)?(e[3]||se.error(e[0]),e[4]=+(e[4]?e[5]+(e[6]||1):2*("even"===e[3]||"odd"===e[3])),e[5]=+(e[7]+e[8]||"odd"===e[3])):e[3]&&se.error(e[0]),e},PSEUDO:function(e){var t,n=!e[6]&&e[2];return G.CHILD.test(e[0])?null:(e[3]?e[2]=e[4]||e[5]||"":n&&X.test(n)&&(t=h(n,!0))&&(t=n.indexOf(")",n.length-t)-n.length)&&(e[0]=e[0].slice(0,t),e[2]=n.slice(0,t)),e.slice(0,3))}},filter:{TAG:function(e){var t=e.replace(te,ne).toLowerCase();return"*"===e?function(){return!0}:function(e){return e.nodeName&&e.nodeName.toLowerCase()===t}},CLASS:function(e){var t=p[e+" "];return t||(t=new RegExp("(^|"+M+")"+e+"("+M+"|$)"))&&p(e,function(e){return t.test("string"==typeof e.className&&e.className||"undefined"!=typeof e.getAttribute&&e.getAttribute("class")||"")})},ATTR:function(n,r,i){return function(e){var t=se.attr(e,n);return null==t?"!="===r:!r||(t+="","="===r?t===i:"!="===r?t!==i:"^="===r?i&&0===t.indexOf(i):"*="===r?i&&-1<t.indexOf(i):"$="===r?i&&t.slice(-i.length)===i:"~="===r?-1<(" "+t.replace(F," ")+" ").indexOf(i):"|="===r&&(t===i||t.slice(0,i.length+1)===i+"-"))}},CHILD:function(h,e,t,g,v){var y="nth"!==h.slice(0,3),m="last"!==h.slice(-4),x="of-type"===e;return 1===g&&0===v?function(e){return!!e.parentNode}:function(e,t,n){var r,i,o,a,s,u,l=y!==m?"nextSibling":"previousSibling",c=e.parentNode,f=x&&e.nodeName.toLowerCase(),p=!n&&!x,d=!1;if(c){if(y){while(l){a=e;while(a=a[l])if(x?a.nodeName.toLowerCase()===f:1===a.nodeType)return!1;u=l="only"===h&&!u&&"nextSibling"}return!0}if(u=[m?c.firstChild:c.lastChild],m&&p){d=(s=(r=(i=(o=(a=c)[k]||(a[k]={}))[a.uniqueID]||(o[a.uniqueID]={}))[h]||[])[0]===S&&r[1])&&r[2],a=s&&c.childNodes[s];while(a=++s&&a&&a[l]||(d=s=0)||u.pop())if(1===a.nodeType&&++d&&a===e){i[h]=[S,s,d];break}}else if(p&&(d=s=(r=(i=(o=(a=e)[k]||(a[k]={}))[a.uniqueID]||(o[a.uniqueID]={}))[h]||[])[0]===S&&r[1]),!1===d)while(a=++s&&a&&a[l]||(d=s=0)||u.pop())if((x?a.nodeName.toLowerCase()===f:1===a.nodeType)&&++d&&(p&&((i=(o=a[k]||(a[k]={}))[a.uniqueID]||(o[a.uniqueID]={}))[h]=[S,d]),a===e))break;return(d-=v)===g||d%g==0&&0<=d/g}}},PSEUDO:function(e,o){var t,a=b.pseudos[e]||b.setFilters[e.toLowerCase()]||se.error("unsupported pseudo: "+e);return a[k]?a(o):1<a.length?(t=[e,e,"",o],b.setFilters.hasOwnProperty(e.toLowerCase())?le(function(e,t){var n,r=a(e,o),i=r.length;while(i--)e[n=P(e,r[i])]=!(t[n]=r[i])}):function(e){return a(e,0,t)}):a}},pseudos:{not:le(function(e){var r=[],i=[],s=f(e.replace(B,"$1"));return s[k]?le(function(e,t,n,r){var i,o=s(e,null,r,[]),a=e.length;while(a--)(i=o[a])&&(e[a]=!(t[a]=i))}):function(e,t,n){return r[0]=e,s(r,null,n,i),r[0]=null,!i.pop()}}),has:le(function(t){return function(e){return 0<se(t,e).length}}),contains:le(function(t){return t=t.replace(te,ne),function(e){return-1<(e.textContent||o(e)).indexOf(t)}}),lang:le(function(n){return V.test(n||"")||se.error("unsupported lang: "+n),n=n.replace(te,ne).toLowerCase(),function(e){var t;do{if(t=E?e.lang:e.getAttribute("xml:lang")||e.getAttribute("lang"))return(t=t.toLowerCase())===n||0===t.indexOf(n+"-")}while((e=e.parentNode)&&1===e.nodeType);return!1}}),target:function(e){var t=n.location&&n.location.hash;return t&&t.slice(1)===e.id},root:function(e){return e===a},focus:function(e){return e===C.activeElement&&(!C.hasFocus||C.hasFocus())&&!!(e.type||e.href||~e.tabIndex)},enabled:ge(!1),disabled:ge(!0),checked:function(e){var t=e.nodeName.toLowerCase();return"input"===t&&!!e.checked||"option"===t&&!!e.selected},selected:function(e){return e.parentNode&&e.parentNode.selectedIndex,!0===e.selected},empty:function(e){for(e=e.firstChild;e;e=e.nextSibling)if(e.nodeType<6)return!1;return!0},parent:function(e){return!b.pseudos.empty(e)},header:function(e){return J.test(e.nodeName)},input:function(e){return Q.test(e.nodeName)},button:function(e){var t=e.nodeName.toLowerCase();return"input"===t&&"button"===e.type||"button"===t},text:function(e){var t;return"input"===e.nodeName.toLowerCase()&&"text"===e.type&&(null==(t=e.getAttribute("type"))||"text"===t.toLowerCase())},first:ve(function(){return[0]}),last:ve(function(e,t){return[t-1]}),eq:ve(function(e,t,n){return[n<0?n+t:n]}),even:ve(function(e,t){for(var n=0;n<t;n+=2)e.push(n);return e}),odd:ve(function(e,t){for(var n=1;n<t;n+=2)e.push(n);return e}),lt:ve(function(e,t,n){for(var r=n<0?n+t:t<n?t:n;0<=--r;)e.push(r);return e}),gt:ve(function(e,t,n){for(var r=n<0?n+t:n;++r<t;)e.push(r);return e})}}).pseudos.nth=b.pseudos.eq,{radio:!0,checkbox:!0,file:!0,password:!0,image:!0})b.pseudos[e]=de(e);for(e in{submit:!0,reset:!0})b.pseudos[e]=he(e);function me(){}function xe(e){for(var t=0,n=e.length,r="";t<n;t++)r+=e[t].value;return r}function be(s,e,t){var u=e.dir,l=e.next,c=l||u,f=t&&"parentNode"===c,p=r++;return e.first?function(e,t,n){while(e=e[u])if(1===e.nodeType||f)return s(e,t,n);return!1}:function(e,t,n){var r,i,o,a=[S,p];if(n){while(e=e[u])if((1===e.nodeType||f)&&s(e,t,n))return!0}else while(e=e[u])if(1===e.nodeType||f)if(i=(o=e[k]||(e[k]={}))[e.uniqueID]||(o[e.uniqueID]={}),l&&l===e.nodeName.toLowerCase())e=e[u]||e;else{if((r=i[c])&&r[0]===S&&r[1]===p)return a[2]=r[2];if((i[c]=a)[2]=s(e,t,n))return!0}return!1}}function we(i){return 1<i.length?function(e,t,n){var r=i.length;while(r--)if(!i[r](e,t,n))return!1;return!0}:i[0]}function Te(e,t,n,r,i){for(var o,a=[],s=0,u=e.length,l=null!=t;s<u;s++)(o=e[s])&&(n&&!n(o,r,i)||(a.push(o),l&&t.push(s)));return a}function Ce(d,h,g,v,y,e){return v&&!v[k]&&(v=Ce(v)),y&&!y[k]&&(y=Ce(y,e)),le(function(e,t,n,r){var i,o,a,s=[],u=[],l=t.length,c=e||function(e,t,n){for(var r=0,i=t.length;r<i;r++)se(e,t[r],n);return n}(h||"*",n.nodeType?[n]:n,[]),f=!d||!e&&h?c:Te(c,s,d,n,r),p=g?y||(e?d:l||v)?[]:t:f;if(g&&g(f,p,n,r),v){i=Te(p,u),v(i,[],n,r),o=i.length;while(o--)(a=i[o])&&(p[u[o]]=!(f[u[o]]=a))}if(e){if(y||d){if(y){i=[],o=p.length;while(o--)(a=p[o])&&i.push(f[o]=a);y(null,p=[],i,r)}o=p.length;while(o--)(a=p[o])&&-1<(i=y?P(e,a):s[o])&&(e[i]=!(t[i]=a))}}else p=Te(p===t?p.splice(l,p.length):p),y?y(null,t,p,r):H.apply(t,p)})}function Ee(e){for(var i,t,n,r=e.length,o=b.relative[e[0].type],a=o||b.relative[" "],s=o?1:0,u=be(function(e){return e===i},a,!0),l=be(function(e){return-1<P(i,e)},a,!0),c=[function(e,t,n){var r=!o&&(n||t!==w)||((i=t).nodeType?u(e,t,n):l(e,t,n));return i=null,r}];s<r;s++)if(t=b.relative[e[s].type])c=[be(we(c),t)];else{if((t=b.filter[e[s].type].apply(null,e[s].matches))[k]){for(n=++s;n<r;n++)if(b.relative[e[n].type])break;return Ce(1<s&&we(c),1<s&&xe(e.slice(0,s-1).concat({value:" "===e[s-2].type?"*":""})).replace(B,"$1"),t,s<n&&Ee(e.slice(s,n)),n<r&&Ee(e=e.slice(n)),n<r&&xe(e))}c.push(t)}return we(c)}return me.prototype=b.filters=b.pseudos,b.setFilters=new me,h=se.tokenize=function(e,t){var n,r,i,o,a,s,u,l=x[e+" "];if(l)return t?0:l.slice(0);a=e,s=[],u=b.preFilter;while(a){for(o in n&&!(r=_.exec(a))||(r&&(a=a.slice(r[0].length)||a),s.push(i=[])),n=!1,(r=z.exec(a))&&(n=r.shift(),i.push({value:n,type:r[0].replace(B," ")}),a=a.slice(n.length)),b.filter)!(r=G[o].exec(a))||u[o]&&!(r=u[o](r))||(n=r.shift(),i.push({value:n,type:o,matches:r}),a=a.slice(n.length));if(!n)break}return t?a.length:a?se.error(e):x(e,s).slice(0)},f=se.compile=function(e,t){var n,v,y,m,x,r,i=[],o=[],a=N[e+" "];if(!a){t||(t=h(e)),n=t.length;while(n--)(a=Ee(t[n]))[k]?i.push(a):o.push(a);(a=N(e,(v=o,m=0<(y=i).length,x=0<v.length,r=function(e,t,n,r,i){var o,a,s,u=0,l="0",c=e&&[],f=[],p=w,d=e||x&&b.find.TAG("*",i),h=S+=null==p?1:Math.random()||.1,g=d.length;for(i&&(w=t===C||t||i);l!==g&&null!=(o=d[l]);l++){if(x&&o){a=0,t||o.ownerDocument===C||(T(o),n=!E);while(s=v[a++])if(s(o,t||C,n)){r.push(o);break}i&&(S=h)}m&&((o=!s&&o)&&u--,e&&c.push(o))}if(u+=l,m&&l!==u){a=0;while(s=y[a++])s(c,f,t,n);if(e){if(0<u)while(l--)c[l]||f[l]||(f[l]=q.call(r));f=Te(f)}H.apply(r,f),i&&!e&&0<f.length&&1<u+y.length&&se.uniqueSort(r)}return i&&(S=h,w=p),c},m?le(r):r))).selector=e}return a},g=se.select=function(e,t,n,r){var i,o,a,s,u,l="function"==typeof e&&e,c=!r&&h(e=l.selector||e);if(n=n||[],1===c.length){if(2<(o=c[0]=c[0].slice(0)).length&&"ID"===(a=o[0]).type&&9===t.nodeType&&E&&b.relative[o[1].type]){if(!(t=(b.find.ID(a.matches[0].replace(te,ne),t)||[])[0]))return n;l&&(t=t.parentNode),e=e.slice(o.shift().value.length)}i=G.needsContext.test(e)?0:o.length;while(i--){if(a=o[i],b.relative[s=a.type])break;if((u=b.find[s])&&(r=u(a.matches[0].replace(te,ne),ee.test(o[0].type)&&ye(t.parentNode)||t))){if(o.splice(i,1),!(e=r.length&&xe(o)))return H.apply(n,r),n;break}}}return(l||f(e,c))(r,t,!E,n,!t||ee.test(e)&&ye(t.parentNode)||t),n},d.sortStable=k.split("").sort(D).join("")===k,d.detectDuplicates=!!l,T(),d.sortDetached=ce(function(e){return 1&e.compareDocumentPosition(C.createElement("fieldset"))}),ce(function(e){return e.innerHTML="<a href='#'></a>","#"===e.firstChild.getAttribute("href")})||fe("type|href|height|width",function(e,t,n){if(!n)return e.getAttribute(t,"type"===t.toLowerCase()?1:2)}),d.attributes&&ce(function(e){return e.innerHTML="<input/>",e.firstChild.setAttribute("value",""),""===e.firstChild.getAttribute("value")})||fe("value",function(e,t,n){if(!n&&"input"===e.nodeName.toLowerCase())return e.defaultValue}),ce(function(e){return null==e.getAttribute("disabled")})||fe(R,function(e,t,n){var r;if(!n)return!0===e[t]?t.toLowerCase():(r=e.getAttributeNode(t))&&r.specified?r.value:null}),se}(C);k.find=h,k.expr=h.selectors,k.expr[":"]=k.expr.pseudos,k.uniqueSort=k.unique=h.uniqueSort,k.text=h.getText,k.isXMLDoc=h.isXML,k.contains=h.contains,k.escapeSelector=h.escape;var T=function(e,t,n){var r=[],i=void 0!==n;while((e=e[t])&&9!==e.nodeType)if(1===e.nodeType){if(i&&k(e).is(n))break;r.push(e)}return r},S=function(e,t){for(var n=[];e;e=e.nextSibling)1===e.nodeType&&e!==t&&n.push(e);return n},N=k.expr.match.needsContext;function A(e,t){return e.nodeName&&e.nodeName.toLowerCase()===t.toLowerCase()}var D=/^<([a-z][^\/\0>:\x20\t\r\n\f]*)[\x20\t\r\n\f]*\/?>(?:<\/\1>|)$/i;function j(e,n,r){return m(n)?k.grep(e,function(e,t){return!!n.call(e,t,e)!==r}):n.nodeType?k.grep(e,function(e){return e===n!==r}):"string"!=typeof n?k.grep(e,function(e){return-1<i.call(n,e)!==r}):k.filter(n,e,r)}k.filter=function(e,t,n){var r=t[0];return n&&(e=":not("+e+")"),1===t.length&&1===r.nodeType?k.find.matchesSelector(r,e)?[r]:[]:k.find.matches(e,k.grep(t,function(e){return 1===e.nodeType}))},k.fn.extend({find:function(e){var t,n,r=this.length,i=this;if("string"!=typeof e)return this.pushStack(k(e).filter(function(){for(t=0;t<r;t++)if(k.contains(i[t],this))return!0}));for(n=this.pushStack([]),t=0;t<r;t++)k.find(e,i[t],n);return 1<r?k.uniqueSort(n):n},filter:function(e){return this.pushStack(j(this,e||[],!1))},not:function(e){return this.pushStack(j(this,e||[],!0))},is:function(e){return!!j(this,"string"==typeof e&&N.test(e)?k(e):e||[],!1).length}});var q,L=/^(?:\s*(<[\w\W]+>)[^>]*|#([\w-]+))$/;(k.fn.init=function(e,t,n){var r,i;if(!e)return this;if(n=n||q,"string"==typeof e){if(!(r="<"===e[0]&&">"===e[e.length-1]&&3<=e.length?[null,e,null]:L.exec(e))||!r[1]&&t)return!t||t.jquery?(t||n).find(e):this.constructor(t).find(e);if(r[1]){if(t=t instanceof k?t[0]:t,k.merge(this,k.parseHTML(r[1],t&&t.nodeType?t.ownerDocument||t:E,!0)),D.test(r[1])&&k.isPlainObject(t))for(r in t)m(this[r])?this[r](t[r]):this.attr(r,t[r]);return this}return(i=E.getElementById(r[2]))&&(this[0]=i,this.length=1),this}return e.nodeType?(this[0]=e,this.length=1,this):m(e)?void 0!==n.ready?n.ready(e):e(k):k.makeArray(e,this)}).prototype=k.fn,q=k(E);var H=/^(?:parents|prev(?:Until|All))/,O={children:!0,contents:!0,next:!0,prev:!0};function P(e,t){while((e=e[t])&&1!==e.nodeType);return e}k.fn.extend({has:function(e){var t=k(e,this),n=t.length;return this.filter(function(){for(var e=0;e<n;e++)if(k.contains(this,t[e]))return!0})},closest:function(e,t){var n,r=0,i=this.length,o=[],a="string"!=typeof e&&k(e);if(!N.test(e))for(;r<i;r++)for(n=this[r];n&&n!==t;n=n.parentNode)if(n.nodeType<11&&(a?-1<a.index(n):1===n.nodeType&&k.find.matchesSelector(n,e))){o.push(n);break}return this.pushStack(1<o.length?k.uniqueSort(o):o)},index:function(e){return e?"string"==typeof e?i.call(k(e),this[0]):i.call(this,e.jquery?e[0]:e):this[0]&&this[0].parentNode?this.first().prevAll().length:-1},add:function(e,t){return this.pushStack(k.uniqueSort(k.merge(this.get(),k(e,t))))},addBack:function(e){return this.add(null==e?this.prevObject:this.prevObject.filter(e))}}),k.each({parent:function(e){var t=e.parentNode;return t&&11!==t.nodeType?t:null},parents:function(e){return T(e,"parentNode")},parentsUntil:function(e,t,n){return T(e,"parentNode",n)},next:function(e){return P(e,"nextSibling")},prev:function(e){return P(e,"previousSibling")},nextAll:function(e){return T(e,"nextSibling")},prevAll:function(e){return T(e,"previousSibling")},nextUntil:function(e,t,n){return T(e,"nextSibling",n)},prevUntil:function(e,t,n){return T(e,"previousSibling",n)},siblings:function(e){return S((e.parentNode||{}).firstChild,e)},children:function(e){return S(e.firstChild)},contents:function(e){return"undefined"!=typeof e.contentDocument?e.contentDocument:(A(e,"template")&&(e=e.content||e),k.merge([],e.childNodes))}},function(r,i){k.fn[r]=function(e,t){var n=k.map(this,i,e);return"Until"!==r.slice(-5)&&(t=e),t&&"string"==typeof t&&(n=k.filter(t,n)),1<this.length&&(O[r]||k.uniqueSort(n),H.test(r)&&n.reverse()),this.pushStack(n)}});var R=/[^\x20\t\r\n\f]+/g;function M(e){return e}function I(e){throw e}function W(e,t,n,r){var i;try{e&&m(i=e.promise)?i.call(e).done(t).fail(n):e&&m(i=e.then)?i.call(e,t,n):t.apply(void 0,[e].slice(r))}catch(e){n.apply(void 0,[e])}}k.Callbacks=function(r){var e,n;r="string"==typeof r?(e=r,n={},k.each(e.match(R)||[],function(e,t){n[t]=!0}),n):k.extend({},r);var i,t,o,a,s=[],u=[],l=-1,c=function(){for(a=a||r.once,o=i=!0;u.length;l=-1){t=u.shift();while(++l<s.length)!1===s[l].apply(t[0],t[1])&&r.stopOnFalse&&(l=s.length,t=!1)}r.memory||(t=!1),i=!1,a&&(s=t?[]:"")},f={add:function(){return s&&(t&&!i&&(l=s.length-1,u.push(t)),function n(e){k.each(e,function(e,t){m(t)?r.unique&&f.has(t)||s.push(t):t&&t.length&&"string"!==w(t)&&n(t)})}(arguments),t&&!i&&c()),this},remove:function(){return k.each(arguments,function(e,t){var n;while(-1<(n=k.inArray(t,s,n)))s.splice(n,1),n<=l&&l--}),this},has:function(e){return e?-1<k.inArray(e,s):0<s.length},empty:function(){return s&&(s=[]),this},disable:function(){return a=u=[],s=t="",this},disabled:function(){return!s},lock:function(){return a=u=[],t||i||(s=t=""),this},locked:function(){return!!a},fireWith:function(e,t){return a||(t=[e,(t=t||[]).slice?t.slice():t],u.push(t),i||c()),this},fire:function(){return f.fireWith(this,arguments),this},fired:function(){return!!o}};return f},k.extend({Deferred:function(e){var o=[["notify","progress",k.Callbacks("memory"),k.Callbacks("memory"),2],["resolve","done",k.Callbacks("once memory"),k.Callbacks("once memory"),0,"resolved"],["reject","fail",k.Callbacks("once memory"),k.Callbacks("once memory"),1,"rejected"]],i="pending",a={state:function(){return i},always:function(){return s.done(arguments).fail(arguments),this},"catch":function(e){return a.then(null,e)},pipe:function(){var i=arguments;return k.Deferred(function(r){k.each(o,function(e,t){var n=m(i[t[4]])&&i[t[4]];s[t[1]](function(){var e=n&&n.apply(this,arguments);e&&m(e.promise)?e.promise().progress(r.notify).done(r.resolve).fail(r.reject):r[t[0]+"With"](this,n?[e]:arguments)})}),i=null}).promise()},then:function(t,n,r){var u=0;function l(i,o,a,s){return function(){var n=this,r=arguments,e=function(){var e,t;if(!(i<u)){if((e=a.apply(n,r))===o.promise())throw new TypeError("Thenable self-resolution");t=e&&("object"==typeof e||"function"==typeof e)&&e.then,m(t)?s?t.call(e,l(u,o,M,s),l(u,o,I,s)):(u++,t.call(e,l(u,o,M,s),l(u,o,I,s),l(u,o,M,o.notifyWith))):(a!==M&&(n=void 0,r=[e]),(s||o.resolveWith)(n,r))}},t=s?e:function(){try{e()}catch(e){k.Deferred.exceptionHook&&k.Deferred.exceptionHook(e,t.stackTrace),u<=i+1&&(a!==I&&(n=void 0,r=[e]),o.rejectWith(n,r))}};i?t():(k.Deferred.getStackHook&&(t.stackTrace=k.Deferred.getStackHook()),C.setTimeout(t))}}return k.Deferred(function(e){o[0][3].add(l(0,e,m(r)?r:M,e.notifyWith)),o[1][3].add(l(0,e,m(t)?t:M)),o[2][3].add(l(0,e,m(n)?n:I))}).promise()},promise:function(e){return null!=e?k.extend(e,a):a}},s={};return k.each(o,function(e,t){var n=t[2],r=t[5];a[t[1]]=n.add,r&&n.add(function(){i=r},o[3-e][2].disable,o[3-e][3].disable,o[0][2].lock,o[0][3].lock),n.add(t[3].fire),s[t[0]]=function(){return s[t[0]+"With"](this===s?void 0:this,arguments),this},s[t[0]+"With"]=n.fireWith}),a.promise(s),e&&e.call(s,s),s},when:function(e){var n=arguments.length,t=n,r=Array(t),i=s.call(arguments),o=k.Deferred(),a=function(t){return function(e){r[t]=this,i[t]=1<arguments.length?s.call(arguments):e,--n||o.resolveWith(r,i)}};if(n<=1&&(W(e,o.done(a(t)).resolve,o.reject,!n),"pending"===o.state()||m(i[t]&&i[t].then)))return o.then();while(t--)W(i[t],a(t),o.reject);return o.promise()}});var $=/^(Eval|Internal|Range|Reference|Syntax|Type|URI)Error$/;k.Deferred.exceptionHook=function(e,t){C.console&&C.console.warn&&e&&$.test(e.name)&&C.console.warn("jQuery.Deferred exception: "+e.message,e.stack,t)},k.readyException=function(e){C.setTimeout(function(){throw e})};var F=k.Deferred();function B(){E.removeEventListener("DOMContentLoaded",B),C.removeEventListener("load",B),k.ready()}k.fn.ready=function(e){return F.then(e)["catch"](function(e){k.readyException(e)}),this},k.extend({isReady:!1,readyWait:1,ready:function(e){(!0===e?--k.readyWait:k.isReady)||(k.isReady=!0)!==e&&0<--k.readyWait||F.resolveWith(E,[k])}}),k.ready.then=F.then,"complete"===E.readyState||"loading"!==E.readyState&&!E.documentElement.doScroll?C.setTimeout(k.ready):(E.addEventListener("DOMContentLoaded",B),C.addEventListener("load",B));var _=function(e,t,n,r,i,o,a){var s=0,u=e.length,l=null==n;if("object"===w(n))for(s in i=!0,n)_(e,t,s,n[s],!0,o,a);else if(void 0!==r&&(i=!0,m(r)||(a=!0),l&&(a?(t.call(e,r),t=null):(l=t,t=function(e,t,n){return l.call(k(e),n)})),t))for(;s<u;s++)t(e[s],n,a?r:r.call(e[s],s,t(e[s],n)));return i?e:l?t.call(e):u?t(e[0],n):o},z=/^-ms-/,U=/-([a-z])/g;function X(e,t){return t.toUpperCase()}function V(e){return e.replace(z,"ms-").replace(U,X)}var G=function(e){return 1===e.nodeType||9===e.nodeType||!+e.nodeType};function Y(){this.expando=k.expando+Y.uid++}Y.uid=1,Y.prototype={cache:function(e){var t=e[this.expando];return t||(t={},G(e)&&(e.nodeType?e[this.expando]=t:Object.defineProperty(e,this.expando,{value:t,configurable:!0}))),t},set:function(e,t,n){var r,i=this.cache(e);if("string"==typeof t)i[V(t)]=n;else for(r in t)i[V(r)]=t[r];return i},get:function(e,t){return void 0===t?this.cache(e):e[this.expando]&&e[this.expando][V(t)]},access:function(e,t,n){return void 0===t||t&&"string"==typeof t&&void 0===n?this.get(e,t):(this.set(e,t,n),void 0!==n?n:t)},remove:function(e,t){var n,r=e[this.expando];if(void 0!==r){if(void 0!==t){n=(t=Array.isArray(t)?t.map(V):(t=V(t))in r?[t]:t.match(R)||[]).length;while(n--)delete r[t[n]]}(void 0===t||k.isEmptyObject(r))&&(e.nodeType?e[this.expando]=void 0:delete e[this.expando])}},hasData:function(e){var t=e[this.expando];return void 0!==t&&!k.isEmptyObject(t)}};var Q=new Y,J=new Y,K=/^(?:\{[\w\W]*\}|\[[\w\W]*\])$/,Z=/[A-Z]/g;function ee(e,t,n){var r,i;if(void 0===n&&1===e.nodeType)if(r="data-"+t.replace(Z,"-$&").toLowerCase(),"string"==typeof(n=e.getAttribute(r))){try{n="true"===(i=n)||"false"!==i&&("null"===i?null:i===+i+""?+i:K.test(i)?JSON.parse(i):i)}catch(e){}J.set(e,t,n)}else n=void 0;return n}k.extend({hasData:function(e){return J.hasData(e)||Q.hasData(e)},data:function(e,t,n){return J.access(e,t,n)},removeData:function(e,t){J.remove(e,t)},_data:function(e,t,n){return Q.access(e,t,n)},_removeData:function(e,t){Q.remove(e,t)}}),k.fn.extend({data:function(n,e){var t,r,i,o=this[0],a=o&&o.attributes;if(void 0===n){if(this.length&&(i=J.get(o),1===o.nodeType&&!Q.get(o,"hasDataAttrs"))){t=a.length;while(t--)a[t]&&0===(r=a[t].name).indexOf("data-")&&(r=V(r.slice(5)),ee(o,r,i[r]));Q.set(o,"hasDataAttrs",!0)}return i}return"object"==typeof n?this.each(function(){J.set(this,n)}):_(this,function(e){var t;if(o&&void 0===e)return void 0!==(t=J.get(o,n))?t:void 0!==(t=ee(o,n))?t:void 0;this.each(function(){J.set(this,n,e)})},null,e,1<arguments.length,null,!0)},removeData:function(e){return this.each(function(){J.remove(this,e)})}}),k.extend({queue:function(e,t,n){var r;if(e)return t=(t||"fx")+"queue",r=Q.get(e,t),n&&(!r||Array.isArray(n)?r=Q.access(e,t,k.makeArray(n)):r.push(n)),r||[]},dequeue:function(e,t){t=t||"fx";var n=k.queue(e,t),r=n.length,i=n.shift(),o=k._queueHooks(e,t);"inprogress"===i&&(i=n.shift(),r--),i&&("fx"===t&&n.unshift("inprogress"),delete o.stop,i.call(e,function(){k.dequeue(e,t)},o)),!r&&o&&o.empty.fire()},_queueHooks:function(e,t){var n=t+"queueHooks";return Q.get(e,n)||Q.access(e,n,{empty:k.Callbacks("once memory").add(function(){Q.remove(e,[t+"queue",n])})})}}),k.fn.extend({queue:function(t,n){var e=2;return"string"!=typeof t&&(n=t,t="fx",e--),arguments.length<e?k.queue(this[0],t):void 0===n?this:this.each(function(){var e=k.queue(this,t,n);k._queueHooks(this,t),"fx"===t&&"inprogress"!==e[0]&&k.dequeue(this,t)})},dequeue:function(e){return this.each(function(){k.dequeue(this,e)})},clearQueue:function(e){return this.queue(e||"fx",[])},promise:function(e,t){var n,r=1,i=k.Deferred(),o=this,a=this.length,s=function(){--r||i.resolveWith(o,[o])};"string"!=typeof e&&(t=e,e=void 0),e=e||"fx";while(a--)(n=Q.get(o[a],e+"queueHooks"))&&n.empty&&(r++,n.empty.add(s));return s(),i.promise(t)}});var te=/[+-]?(?:\d*\.|)\d+(?:[eE][+-]?\d+|)/.source,ne=new RegExp("^(?:([+-])=|)("+te+")([a-z%]*)$","i"),re=["Top","Right","Bottom","Left"],ie=E.documentElement,oe=function(e){return k.contains(e.ownerDocument,e)},ae={composed:!0};ie.getRootNode&&(oe=function(e){return k.contains(e.ownerDocument,e)||e.getRootNode(ae)===e.ownerDocument});var se=function(e,t){return"none"===(e=t||e).style.display||""===e.style.display&&oe(e)&&"none"===k.css(e,"display")},ue=function(e,t,n,r){var i,o,a={};for(o in t)a[o]=e.style[o],e.style[o]=t[o];for(o in i=n.apply(e,r||[]),t)e.style[o]=a[o];return i};function le(e,t,n,r){var i,o,a=20,s=r?function(){return r.cur()}:function(){return k.css(e,t,"")},u=s(),l=n&&n[3]||(k.cssNumber[t]?"":"px"),c=e.nodeType&&(k.cssNumber[t]||"px"!==l&&+u)&&ne.exec(k.css(e,t));if(c&&c[3]!==l){u/=2,l=l||c[3],c=+u||1;while(a--)k.style(e,t,c+l),(1-o)*(1-(o=s()/u||.5))<=0&&(a=0),c/=o;c*=2,k.style(e,t,c+l),n=n||[]}return n&&(c=+c||+u||0,i=n[1]?c+(n[1]+1)*n[2]:+n[2],r&&(r.unit=l,r.start=c,r.end=i)),i}var ce={};function fe(e,t){for(var n,r,i,o,a,s,u,l=[],c=0,f=e.length;c<f;c++)(r=e[c]).style&&(n=r.style.display,t?("none"===n&&(l[c]=Q.get(r,"display")||null,l[c]||(r.style.display="")),""===r.style.display&&se(r)&&(l[c]=(u=a=o=void 0,a=(i=r).ownerDocument,s=i.nodeName,(u=ce[s])||(o=a.body.appendChild(a.createElement(s)),u=k.css(o,"display"),o.parentNode.removeChild(o),"none"===u&&(u="block"),ce[s]=u)))):"none"!==n&&(l[c]="none",Q.set(r,"display",n)));for(c=0;c<f;c++)null!=l[c]&&(e[c].style.display=l[c]);return e}k.fn.extend({show:function(){return fe(this,!0)},hide:function(){return fe(this)},toggle:function(e){return"boolean"==typeof e?e?this.show():this.hide():this.each(function(){se(this)?k(this).show():k(this).hide()})}});var pe=/^(?:checkbox|radio)$/i,de=/<([a-z][^\/\0>\x20\t\r\n\f]*)/i,he=/^$|^module$|\/(?:java|ecma)script/i,ge={option:[1,"<select multiple='multiple'>","</select>"],thead:[1,"<table>","</table>"],col:[2,"<table><colgroup>","</colgroup></table>"],tr:[2,"<table><tbody>","</tbody></table>"],td:[3,"<table><tbody><tr>","</tr></tbody></table>"],_default:[0,"",""]};function ve(e,t){var n;return n="undefined"!=typeof e.getElementsByTagName?e.getElementsByTagName(t||"*"):"undefined"!=typeof e.querySelectorAll?e.querySelectorAll(t||"*"):[],void 0===t||t&&A(e,t)?k.merge([e],n):n}function ye(e,t){for(var n=0,r=e.length;n<r;n++)Q.set(e[n],"globalEval",!t||Q.get(t[n],"globalEval"))}ge.optgroup=ge.option,ge.tbody=ge.tfoot=ge.colgroup=ge.caption=ge.thead,ge.th=ge.td;var me,xe,be=/<|&#?\w+;/;function we(e,t,n,r,i){for(var o,a,s,u,l,c,f=t.createDocumentFragment(),p=[],d=0,h=e.length;d<h;d++)if((o=e[d])||0===o)if("object"===w(o))k.merge(p,o.nodeType?[o]:o);else if(be.test(o)){a=a||f.appendChild(t.createElement("div")),s=(de.exec(o)||["",""])[1].toLowerCase(),u=ge[s]||ge._default,a.innerHTML=u[1]+k.htmlPrefilter(o)+u[2],c=u[0];while(c--)a=a.lastChild;k.merge(p,a.childNodes),(a=f.firstChild).textContent=""}else p.push(t.createTextNode(o));f.textContent="",d=0;while(o=p[d++])if(r&&-1<k.inArray(o,r))i&&i.push(o);else if(l=oe(o),a=ve(f.appendChild(o),"script"),l&&ye(a),n){c=0;while(o=a[c++])he.test(o.type||"")&&n.push(o)}return f}me=E.createDocumentFragment().appendChild(E.createElement("div")),(xe=E.createElement("input")).setAttribute("type","radio"),xe.setAttribute("checked","checked"),xe.setAttribute("name","t"),me.appendChild(xe),y.checkClone=me.cloneNode(!0).cloneNode(!0).lastChild.checked,me.innerHTML="<textarea>x</textarea>",y.noCloneChecked=!!me.cloneNode(!0).lastChild.defaultValue;var Te=/^key/,Ce=/^(?:mouse|pointer|contextmenu|drag|drop)|click/,Ee=/^([^.]*)(?:\.(.+)|)/;function ke(){return!0}function Se(){return!1}function Ne(e,t){return e===function(){try{return E.activeElement}catch(e){}}()==("focus"===t)}function Ae(e,t,n,r,i,o){var a,s;if("object"==typeof t){for(s in"string"!=typeof n&&(r=r||n,n=void 0),t)Ae(e,s,n,r,t[s],o);return e}if(null==r&&null==i?(i=n,r=n=void 0):null==i&&("string"==typeof n?(i=r,r=void 0):(i=r,r=n,n=void 0)),!1===i)i=Se;else if(!i)return e;return 1===o&&(a=i,(i=function(e){return k().off(e),a.apply(this,arguments)}).guid=a.guid||(a.guid=k.guid++)),e.each(function(){k.event.add(this,t,i,r,n)})}function De(e,i,o){o?(Q.set(e,i,!1),k.event.add(e,i,{namespace:!1,handler:function(e){var t,n,r=Q.get(this,i);if(1&e.isTrigger&&this[i]){if(r.length)(k.event.special[i]||{}).delegateType&&e.stopPropagation();else if(r=s.call(arguments),Q.set(this,i,r),t=o(this,i),this[i](),r!==(n=Q.get(this,i))||t?Q.set(this,i,!1):n={},r!==n)return e.stopImmediatePropagation(),e.preventDefault(),n.value}else r.length&&(Q.set(this,i,{value:k.event.trigger(k.extend(r[0],k.Event.prototype),r.slice(1),this)}),e.stopImmediatePropagation())}})):void 0===Q.get(e,i)&&k.event.add(e,i,ke)}k.event={global:{},add:function(t,e,n,r,i){var o,a,s,u,l,c,f,p,d,h,g,v=Q.get(t);if(v){n.handler&&(n=(o=n).handler,i=o.selector),i&&k.find.matchesSelector(ie,i),n.guid||(n.guid=k.guid++),(u=v.events)||(u=v.events={}),(a=v.handle)||(a=v.handle=function(e){return"undefined"!=typeof k&&k.event.triggered!==e.type?k.event.dispatch.apply(t,arguments):void 0}),l=(e=(e||"").match(R)||[""]).length;while(l--)d=g=(s=Ee.exec(e[l])||[])[1],h=(s[2]||"").split(".").sort(),d&&(f=k.event.special[d]||{},d=(i?f.delegateType:f.bindType)||d,f=k.event.special[d]||{},c=k.extend({type:d,origType:g,data:r,handler:n,guid:n.guid,selector:i,needsContext:i&&k.expr.match.needsContext.test(i),namespace:h.join(".")},o),(p=u[d])||((p=u[d]=[]).delegateCount=0,f.setup&&!1!==f.setup.call(t,r,h,a)||t.addEventListener&&t.addEventListener(d,a)),f.add&&(f.add.call(t,c),c.handler.guid||(c.handler.guid=n.guid)),i?p.splice(p.delegateCount++,0,c):p.push(c),k.event.global[d]=!0)}},remove:function(e,t,n,r,i){var o,a,s,u,l,c,f,p,d,h,g,v=Q.hasData(e)&&Q.get(e);if(v&&(u=v.events)){l=(t=(t||"").match(R)||[""]).length;while(l--)if(d=g=(s=Ee.exec(t[l])||[])[1],h=(s[2]||"").split(".").sort(),d){f=k.event.special[d]||{},p=u[d=(r?f.delegateType:f.bindType)||d]||[],s=s[2]&&new RegExp("(^|\\.)"+h.join("\\.(?:.*\\.|)")+"(\\.|$)"),a=o=p.length;while(o--)c=p[o],!i&&g!==c.origType||n&&n.guid!==c.guid||s&&!s.test(c.namespace)||r&&r!==c.selector&&("**"!==r||!c.selector)||(p.splice(o,1),c.selector&&p.delegateCount--,f.remove&&f.remove.call(e,c));a&&!p.length&&(f.teardown&&!1!==f.teardown.call(e,h,v.handle)||k.removeEvent(e,d,v.handle),delete u[d])}else for(d in u)k.event.remove(e,d+t[l],n,r,!0);k.isEmptyObject(u)&&Q.remove(e,"handle events")}},dispatch:function(e){var t,n,r,i,o,a,s=k.event.fix(e),u=new Array(arguments.length),l=(Q.get(this,"events")||{})[s.type]||[],c=k.event.special[s.type]||{};for(u[0]=s,t=1;t<arguments.length;t++)u[t]=arguments[t];if(s.delegateTarget=this,!c.preDispatch||!1!==c.preDispatch.call(this,s)){a=k.event.handlers.call(this,s,l),t=0;while((i=a[t++])&&!s.isPropagationStopped()){s.currentTarget=i.elem,n=0;while((o=i.handlers[n++])&&!s.isImmediatePropagationStopped())s.rnamespace&&!1!==o.namespace&&!s.rnamespace.test(o.namespace)||(s.handleObj=o,s.data=o.data,void 0!==(r=((k.event.special[o.origType]||{}).handle||o.handler).apply(i.elem,u))&&!1===(s.result=r)&&(s.preventDefault(),s.stopPropagation()))}return c.postDispatch&&c.postDispatch.call(this,s),s.result}},handlers:function(e,t){var n,r,i,o,a,s=[],u=t.delegateCount,l=e.target;if(u&&l.nodeType&&!("click"===e.type&&1<=e.button))for(;l!==this;l=l.parentNode||this)if(1===l.nodeType&&("click"!==e.type||!0!==l.disabled)){for(o=[],a={},n=0;n<u;n++)void 0===a[i=(r=t[n]).selector+" "]&&(a[i]=r.needsContext?-1<k(i,this).index(l):k.find(i,this,null,[l]).length),a[i]&&o.push(r);o.length&&s.push({elem:l,handlers:o})}return l=this,u<t.length&&s.push({elem:l,handlers:t.slice(u)}),s},addProp:function(t,e){Object.defineProperty(k.Event.prototype,t,{enumerable:!0,configurable:!0,get:m(e)?function(){if(this.originalEvent)return e(this.originalEvent)}:function(){if(this.originalEvent)return this.originalEvent[t]},set:function(e){Object.defineProperty(this,t,{enumerable:!0,configurable:!0,writable:!0,value:e})}})},fix:function(e){return e[k.expando]?e:new k.Event(e)},special:{load:{noBubble:!0},click:{setup:function(e){var t=this||e;return pe.test(t.type)&&t.click&&A(t,"input")&&De(t,"click",ke),!1},trigger:function(e){var t=this||e;return pe.test(t.type)&&t.click&&A(t,"input")&&De(t,"click"),!0},_default:function(e){var t=e.target;return pe.test(t.type)&&t.click&&A(t,"input")&&Q.get(t,"click")||A(t,"a")}},beforeunload:{postDispatch:function(e){void 0!==e.result&&e.originalEvent&&(e.originalEvent.returnValue=e.result)}}}},k.removeEvent=function(e,t,n){e.removeEventListener&&e.removeEventListener(t,n)},k.Event=function(e,t){if(!(this instanceof k.Event))return new k.Event(e,t);e&&e.type?(this.originalEvent=e,this.type=e.type,this.isDefaultPrevented=e.defaultPrevented||void 0===e.defaultPrevented&&!1===e.returnValue?ke:Se,this.target=e.target&&3===e.target.nodeType?e.target.parentNode:e.target,this.currentTarget=e.currentTarget,this.relatedTarget=e.relatedTarget):this.type=e,t&&k.extend(this,t),this.timeStamp=e&&e.timeStamp||Date.now(),this[k.expando]=!0},k.Event.prototype={constructor:k.Event,isDefaultPrevented:Se,isPropagationStopped:Se,isImmediatePropagationStopped:Se,isSimulated:!1,preventDefault:function(){var e=this.originalEvent;this.isDefaultPrevented=ke,e&&!this.isSimulated&&e.preventDefault()},stopPropagation:function(){var e=this.originalEvent;this.isPropagationStopped=ke,e&&!this.isSimulated&&e.stopPropagation()},stopImmediatePropagation:function(){var e=this.originalEvent;this.isImmediatePropagationStopped=ke,e&&!this.isSimulated&&e.stopImmediatePropagation(),this.stopPropagation()}},k.each({altKey:!0,bubbles:!0,cancelable:!0,changedTouches:!0,ctrlKey:!0,detail:!0,eventPhase:!0,metaKey:!0,pageX:!0,pageY:!0,shiftKey:!0,view:!0,"char":!0,code:!0,charCode:!0,key:!0,keyCode:!0,button:!0,buttons:!0,clientX:!0,clientY:!0,offsetX:!0,offsetY:!0,pointerId:!0,pointerType:!0,screenX:!0,screenY:!0,targetTouches:!0,toElement:!0,touches:!0,which:function(e){var t=e.button;return null==e.which&&Te.test(e.type)?null!=e.charCode?e.charCode:e.keyCode:!e.which&&void 0!==t&&Ce.test(e.type)?1&t?1:2&t?3:4&t?2:0:e.which}},k.event.addProp),k.each({focus:"focusin",blur:"focusout"},function(e,t){k.event.special[e]={setup:function(){return De(this,e,Ne),!1},trigger:function(){return De(this,e),!0},delegateType:t}}),k.each({mouseenter:"mouseover",mouseleave:"mouseout",pointerenter:"pointerover",pointerleave:"pointerout"},function(e,i){k.event.special[e]={delegateType:i,bindType:i,handle:function(e){var t,n=e.relatedTarget,r=e.handleObj;return n&&(n===this||k.contains(this,n))||(e.type=r.origType,t=r.handler.apply(this,arguments),e.type=i),t}}}),k.fn.extend({on:function(e,t,n,r){return Ae(this,e,t,n,r)},one:function(e,t,n,r){return Ae(this,e,t,n,r,1)},off:function(e,t,n){var r,i;if(e&&e.preventDefault&&e.handleObj)return r=e.handleObj,k(e.delegateTarget).off(r.namespace?r.origType+"."+r.namespace:r.origType,r.selector,r.handler),this;if("object"==typeof e){for(i in e)this.off(i,t,e[i]);return this}return!1!==t&&"function"!=typeof t||(n=t,t=void 0),!1===n&&(n=Se),this.each(function(){k.event.remove(this,e,n,t)})}});var je=/<(?!area|br|col|embed|hr|img|input|link|meta|param)(([a-z][^\/\0>\x20\t\r\n\f]*)[^>]*)\/>/gi,qe=/<script|<style|<link/i,Le=/checked\s*(?:[^=]|=\s*.checked.)/i,He=/^\s*<!(?:\[CDATA\[|--)|(?:\]\]|--)>\s*$/g;function Oe(e,t){return A(e,"table")&&A(11!==t.nodeType?t:t.firstChild,"tr")&&k(e).children("tbody")[0]||e}function Pe(e){return e.type=(null!==e.getAttribute("type"))+"/"+e.type,e}function Re(e){return"true/"===(e.type||"").slice(0,5)?e.type=e.type.slice(5):e.removeAttribute("type"),e}function Me(e,t){var n,r,i,o,a,s,u,l;if(1===t.nodeType){if(Q.hasData(e)&&(o=Q.access(e),a=Q.set(t,o),l=o.events))for(i in delete a.handle,a.events={},l)for(n=0,r=l[i].length;n<r;n++)k.event.add(t,i,l[i][n]);J.hasData(e)&&(s=J.access(e),u=k.extend({},s),J.set(t,u))}}function Ie(n,r,i,o){r=g.apply([],r);var e,t,a,s,u,l,c=0,f=n.length,p=f-1,d=r[0],h=m(d);if(h||1<f&&"string"==typeof d&&!y.checkClone&&Le.test(d))return n.each(function(e){var t=n.eq(e);h&&(r[0]=d.call(this,e,t.html())),Ie(t,r,i,o)});if(f&&(t=(e=we(r,n[0].ownerDocument,!1,n,o)).firstChild,1===e.childNodes.length&&(e=t),t||o)){for(s=(a=k.map(ve(e,"script"),Pe)).length;c<f;c++)u=e,c!==p&&(u=k.clone(u,!0,!0),s&&k.merge(a,ve(u,"script"))),i.call(n[c],u,c);if(s)for(l=a[a.length-1].ownerDocument,k.map(a,Re),c=0;c<s;c++)u=a[c],he.test(u.type||"")&&!Q.access(u,"globalEval")&&k.contains(l,u)&&(u.src&&"module"!==(u.type||"").toLowerCase()?k._evalUrl&&!u.noModule&&k._evalUrl(u.src,{nonce:u.nonce||u.getAttribute("nonce")}):b(u.textContent.replace(He,""),u,l))}return n}function We(e,t,n){for(var r,i=t?k.filter(t,e):e,o=0;null!=(r=i[o]);o++)n||1!==r.nodeType||k.cleanData(ve(r)),r.parentNode&&(n&&oe(r)&&ye(ve(r,"script")),r.parentNode.removeChild(r));return e}k.extend({htmlPrefilter:function(e){return e.replace(je,"<$1></$2>")},clone:function(e,t,n){var r,i,o,a,s,u,l,c=e.cloneNode(!0),f=oe(e);if(!(y.noCloneChecked||1!==e.nodeType&&11!==e.nodeType||k.isXMLDoc(e)))for(a=ve(c),r=0,i=(o=ve(e)).length;r<i;r++)s=o[r],u=a[r],void 0,"input"===(l=u.nodeName.toLowerCase())&&pe.test(s.type)?u.checked=s.checked:"input"!==l&&"textarea"!==l||(u.defaultValue=s.defaultValue);if(t)if(n)for(o=o||ve(e),a=a||ve(c),r=0,i=o.length;r<i;r++)Me(o[r],a[r]);else Me(e,c);return 0<(a=ve(c,"script")).length&&ye(a,!f&&ve(e,"script")),c},cleanData:function(e){for(var t,n,r,i=k.event.special,o=0;void 0!==(n=e[o]);o++)if(G(n)){if(t=n[Q.expando]){if(t.events)for(r in t.events)i[r]?k.event.remove(n,r):k.removeEvent(n,r,t.handle);n[Q.expando]=void 0}n[J.expando]&&(n[J.expando]=void 0)}}}),k.fn.extend({detach:function(e){return We(this,e,!0)},remove:function(e){return We(this,e)},text:function(e){return _(this,function(e){return void 0===e?k.text(this):this.empty().each(function(){1!==this.nodeType&&11!==this.nodeType&&9!==this.nodeType||(this.textContent=e)})},null,e,arguments.length)},append:function(){return Ie(this,arguments,function(e){1!==this.nodeType&&11!==this.nodeType&&9!==this.nodeType||Oe(this,e).appendChild(e)})},prepend:function(){return Ie(this,arguments,function(e){if(1===this.nodeType||11===this.nodeType||9===this.nodeType){var t=Oe(this,e);t.insertBefore(e,t.firstChild)}})},before:function(){return Ie(this,arguments,function(e){this.parentNode&&this.parentNode.insertBefore(e,this)})},after:function(){return Ie(this,arguments,function(e){this.parentNode&&this.parentNode.insertBefore(e,this.nextSibling)})},empty:function(){for(var e,t=0;null!=(e=this[t]);t++)1===e.nodeType&&(k.cleanData(ve(e,!1)),e.textContent="");return this},clone:function(e,t){return e=null!=e&&e,t=null==t?e:t,this.map(function(){return k.clone(this,e,t)})},html:function(e){return _(this,function(e){var t=this[0]||{},n=0,r=this.length;if(void 0===e&&1===t.nodeType)return t.innerHTML;if("string"==typeof e&&!qe.test(e)&&!ge[(de.exec(e)||["",""])[1].toLowerCase()]){e=k.htmlPrefilter(e);try{for(;n<r;n++)1===(t=this[n]||{}).nodeType&&(k.cleanData(ve(t,!1)),t.innerHTML=e);t=0}catch(e){}}t&&this.empty().append(e)},null,e,arguments.length)},replaceWith:function(){var n=[];return Ie(this,arguments,function(e){var t=this.parentNode;k.inArray(this,n)<0&&(k.cleanData(ve(this)),t&&t.replaceChild(e,this))},n)}}),k.each({appendTo:"append",prependTo:"prepend",insertBefore:"before",insertAfter:"after",replaceAll:"replaceWith"},function(e,a){k.fn[e]=function(e){for(var t,n=[],r=k(e),i=r.length-1,o=0;o<=i;o++)t=o===i?this:this.clone(!0),k(r[o])[a](t),u.apply(n,t.get());return this.pushStack(n)}});var $e=new RegExp("^("+te+")(?!px)[a-z%]+$","i"),Fe=function(e){var t=e.ownerDocument.defaultView;return t&&t.opener||(t=C),t.getComputedStyle(e)},Be=new RegExp(re.join("|"),"i");function _e(e,t,n){var r,i,o,a,s=e.style;return(n=n||Fe(e))&&(""!==(a=n.getPropertyValue(t)||n[t])||oe(e)||(a=k.style(e,t)),!y.pixelBoxStyles()&&$e.test(a)&&Be.test(t)&&(r=s.width,i=s.minWidth,o=s.maxWidth,s.minWidth=s.maxWidth=s.width=a,a=n.width,s.width=r,s.minWidth=i,s.maxWidth=o)),void 0!==a?a+"":a}function ze(e,t){return{get:function(){if(!e())return(this.get=t).apply(this,arguments);delete this.get}}}!function(){function e(){if(u){s.style.cssText="position:absolute;left:-11111px;width:60px;margin-top:1px;padding:0;border:0",u.style.cssText="position:relative;display:block;box-sizing:border-box;overflow:scroll;margin:auto;border:1px;padding:1px;width:60%;top:1%",ie.appendChild(s).appendChild(u);var e=C.getComputedStyle(u);n="1%"!==e.top,a=12===t(e.marginLeft),u.style.right="60%",o=36===t(e.right),r=36===t(e.width),u.style.position="absolute",i=12===t(u.offsetWidth/3),ie.removeChild(s),u=null}}function t(e){return Math.round(parseFloat(e))}var n,r,i,o,a,s=E.createElement("div"),u=E.createElement("div");u.style&&(u.style.backgroundClip="content-box",u.cloneNode(!0).style.backgroundClip="",y.clearCloneStyle="content-box"===u.style.backgroundClip,k.extend(y,{boxSizingReliable:function(){return e(),r},pixelBoxStyles:function(){return e(),o},pixelPosition:function(){return e(),n},reliableMarginLeft:function(){return e(),a},scrollboxSize:function(){return e(),i}}))}();var Ue=["Webkit","Moz","ms"],Xe=E.createElement("div").style,Ve={};function Ge(e){var t=k.cssProps[e]||Ve[e];return t||(e in Xe?e:Ve[e]=function(e){var t=e[0].toUpperCase()+e.slice(1),n=Ue.length;while(n--)if((e=Ue[n]+t)in Xe)return e}(e)||e)}var Ye=/^(none|table(?!-c[ea]).+)/,Qe=/^--/,Je={position:"absolute",visibility:"hidden",display:"block"},Ke={letterSpacing:"0",fontWeight:"400"};function Ze(e,t,n){var r=ne.exec(t);return r?Math.max(0,r[2]-(n||0))+(r[3]||"px"):t}function et(e,t,n,r,i,o){var a="width"===t?1:0,s=0,u=0;if(n===(r?"border":"content"))return 0;for(;a<4;a+=2)"margin"===n&&(u+=k.css(e,n+re[a],!0,i)),r?("content"===n&&(u-=k.css(e,"padding"+re[a],!0,i)),"margin"!==n&&(u-=k.css(e,"border"+re[a]+"Width",!0,i))):(u+=k.css(e,"padding"+re[a],!0,i),"padding"!==n?u+=k.css(e,"border"+re[a]+"Width",!0,i):s+=k.css(e,"border"+re[a]+"Width",!0,i));return!r&&0<=o&&(u+=Math.max(0,Math.ceil(e["offset"+t[0].toUpperCase()+t.slice(1)]-o-u-s-.5))||0),u}function tt(e,t,n){var r=Fe(e),i=(!y.boxSizingReliable()||n)&&"border-box"===k.css(e,"boxSizing",!1,r),o=i,a=_e(e,t,r),s="offset"+t[0].toUpperCase()+t.slice(1);if($e.test(a)){if(!n)return a;a="auto"}return(!y.boxSizingReliable()&&i||"auto"===a||!parseFloat(a)&&"inline"===k.css(e,"display",!1,r))&&e.getClientRects().length&&(i="border-box"===k.css(e,"boxSizing",!1,r),(o=s in e)&&(a=e[s])),(a=parseFloat(a)||0)+et(e,t,n||(i?"border":"content"),o,r,a)+"px"}function nt(e,t,n,r,i){return new nt.prototype.init(e,t,n,r,i)}k.extend({cssHooks:{opacity:{get:function(e,t){if(t){var n=_e(e,"opacity");return""===n?"1":n}}}},cssNumber:{animationIterationCount:!0,columnCount:!0,fillOpacity:!0,flexGrow:!0,flexShrink:!0,fontWeight:!0,gridArea:!0,gridColumn:!0,gridColumnEnd:!0,gridColumnStart:!0,gridRow:!0,gridRowEnd:!0,gridRowStart:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,widows:!0,zIndex:!0,zoom:!0},cssProps:{},style:function(e,t,n,r){if(e&&3!==e.nodeType&&8!==e.nodeType&&e.style){var i,o,a,s=V(t),u=Qe.test(t),l=e.style;if(u||(t=Ge(s)),a=k.cssHooks[t]||k.cssHooks[s],void 0===n)return a&&"get"in a&&void 0!==(i=a.get(e,!1,r))?i:l[t];"string"===(o=typeof n)&&(i=ne.exec(n))&&i[1]&&(n=le(e,t,i),o="number"),null!=n&&n==n&&("number"!==o||u||(n+=i&&i[3]||(k.cssNumber[s]?"":"px")),y.clearCloneStyle||""!==n||0!==t.indexOf("background")||(l[t]="inherit"),a&&"set"in a&&void 0===(n=a.set(e,n,r))||(u?l.setProperty(t,n):l[t]=n))}},css:function(e,t,n,r){var i,o,a,s=V(t);return Qe.test(t)||(t=Ge(s)),(a=k.cssHooks[t]||k.cssHooks[s])&&"get"in a&&(i=a.get(e,!0,n)),void 0===i&&(i=_e(e,t,r)),"normal"===i&&t in Ke&&(i=Ke[t]),""===n||n?(o=parseFloat(i),!0===n||isFinite(o)?o||0:i):i}}),k.each(["height","width"],function(e,u){k.cssHooks[u]={get:function(e,t,n){if(t)return!Ye.test(k.css(e,"display"))||e.getClientRects().length&&e.getBoundingClientRect().width?tt(e,u,n):ue(e,Je,function(){return tt(e,u,n)})},set:function(e,t,n){var r,i=Fe(e),o=!y.scrollboxSize()&&"absolute"===i.position,a=(o||n)&&"border-box"===k.css(e,"boxSizing",!1,i),s=n?et(e,u,n,a,i):0;return a&&o&&(s-=Math.ceil(e["offset"+u[0].toUpperCase()+u.slice(1)]-parseFloat(i[u])-et(e,u,"border",!1,i)-.5)),s&&(r=ne.exec(t))&&"px"!==(r[3]||"px")&&(e.style[u]=t,t=k.css(e,u)),Ze(0,t,s)}}}),k.cssHooks.marginLeft=ze(y.reliableMarginLeft,function(e,t){if(t)return(parseFloat(_e(e,"marginLeft"))||e.getBoundingClientRect().left-ue(e,{marginLeft:0},function(){return e.getBoundingClientRect().left}))+"px"}),k.each({margin:"",padding:"",border:"Width"},function(i,o){k.cssHooks[i+o]={expand:function(e){for(var t=0,n={},r="string"==typeof e?e.split(" "):[e];t<4;t++)n[i+re[t]+o]=r[t]||r[t-2]||r[0];return n}},"margin"!==i&&(k.cssHooks[i+o].set=Ze)}),k.fn.extend({css:function(e,t){return _(this,function(e,t,n){var r,i,o={},a=0;if(Array.isArray(t)){for(r=Fe(e),i=t.length;a<i;a++)o[t[a]]=k.css(e,t[a],!1,r);return o}return void 0!==n?k.style(e,t,n):k.css(e,t)},e,t,1<arguments.length)}}),((k.Tween=nt).prototype={constructor:nt,init:function(e,t,n,r,i,o){this.elem=e,this.prop=n,this.easing=i||k.easing._default,this.options=t,this.start=this.now=this.cur(),this.end=r,this.unit=o||(k.cssNumber[n]?"":"px")},cur:function(){var e=nt.propHooks[this.prop];return e&&e.get?e.get(this):nt.propHooks._default.get(this)},run:function(e){var t,n=nt.propHooks[this.prop];return this.options.duration?this.pos=t=k.easing[this.easing](e,this.options.duration*e,0,1,this.options.duration):this.pos=t=e,this.now=(this.end-this.start)*t+this.start,this.options.step&&this.options.step.call(this.elem,this.now,this),n&&n.set?n.set(this):nt.propHooks._default.set(this),this}}).init.prototype=nt.prototype,(nt.propHooks={_default:{get:function(e){var t;return 1!==e.elem.nodeType||null!=e.elem[e.prop]&&null==e.elem.style[e.prop]?e.elem[e.prop]:(t=k.css(e.elem,e.prop,""))&&"auto"!==t?t:0},set:function(e){k.fx.step[e.prop]?k.fx.step[e.prop](e):1!==e.elem.nodeType||!k.cssHooks[e.prop]&&null==e.elem.style[Ge(e.prop)]?e.elem[e.prop]=e.now:k.style(e.elem,e.prop,e.now+e.unit)}}}).scrollTop=nt.propHooks.scrollLeft={set:function(e){e.elem.nodeType&&e.elem.parentNode&&(e.elem[e.prop]=e.now)}},k.easing={linear:function(e){return e},swing:function(e){return.5-Math.cos(e*Math.PI)/2},_default:"swing"},k.fx=nt.prototype.init,k.fx.step={};var rt,it,ot,at,st=/^(?:toggle|show|hide)$/,ut=/queueHooks$/;function lt(){it&&(!1===E.hidden&&C.requestAnimationFrame?C.requestAnimationFrame(lt):C.setTimeout(lt,k.fx.interval),k.fx.tick())}function ct(){return C.setTimeout(function(){rt=void 0}),rt=Date.now()}function ft(e,t){var n,r=0,i={height:e};for(t=t?1:0;r<4;r+=2-t)i["margin"+(n=re[r])]=i["padding"+n]=e;return t&&(i.opacity=i.width=e),i}function pt(e,t,n){for(var r,i=(dt.tweeners[t]||[]).concat(dt.tweeners["*"]),o=0,a=i.length;o<a;o++)if(r=i[o].call(n,t,e))return r}function dt(o,e,t){var n,a,r=0,i=dt.prefilters.length,s=k.Deferred().always(function(){delete u.elem}),u=function(){if(a)return!1;for(var e=rt||ct(),t=Math.max(0,l.startTime+l.duration-e),n=1-(t/l.duration||0),r=0,i=l.tweens.length;r<i;r++)l.tweens[r].run(n);return s.notifyWith(o,[l,n,t]),n<1&&i?t:(i||s.notifyWith(o,[l,1,0]),s.resolveWith(o,[l]),!1)},l=s.promise({elem:o,props:k.extend({},e),opts:k.extend(!0,{specialEasing:{},easing:k.easing._default},t),originalProperties:e,originalOptions:t,startTime:rt||ct(),duration:t.duration,tweens:[],createTween:function(e,t){var n=k.Tween(o,l.opts,e,t,l.opts.specialEasing[e]||l.opts.easing);return l.tweens.push(n),n},stop:function(e){var t=0,n=e?l.tweens.length:0;if(a)return this;for(a=!0;t<n;t++)l.tweens[t].run(1);return e?(s.notifyWith(o,[l,1,0]),s.resolveWith(o,[l,e])):s.rejectWith(o,[l,e]),this}}),c=l.props;for(!function(e,t){var n,r,i,o,a;for(n in e)if(i=t[r=V(n)],o=e[n],Array.isArray(o)&&(i=o[1],o=e[n]=o[0]),n!==r&&(e[r]=o,delete e[n]),(a=k.cssHooks[r])&&"expand"in a)for(n in o=a.expand(o),delete e[r],o)n in e||(e[n]=o[n],t[n]=i);else t[r]=i}(c,l.opts.specialEasing);r<i;r++)if(n=dt.prefilters[r].call(l,o,c,l.opts))return m(n.stop)&&(k._queueHooks(l.elem,l.opts.queue).stop=n.stop.bind(n)),n;return k.map(c,pt,l),m(l.opts.start)&&l.opts.start.call(o,l),l.progress(l.opts.progress).done(l.opts.done,l.opts.complete).fail(l.opts.fail).always(l.opts.always),k.fx.timer(k.extend(u,{elem:o,anim:l,queue:l.opts.queue})),l}k.Animation=k.extend(dt,{tweeners:{"*":[function(e,t){var n=this.createTween(e,t);return le(n.elem,e,ne.exec(t),n),n}]},tweener:function(e,t){m(e)?(t=e,e=["*"]):e=e.match(R);for(var n,r=0,i=e.length;r<i;r++)n=e[r],dt.tweeners[n]=dt.tweeners[n]||[],dt.tweeners[n].unshift(t)},prefilters:[function(e,t,n){var r,i,o,a,s,u,l,c,f="width"in t||"height"in t,p=this,d={},h=e.style,g=e.nodeType&&se(e),v=Q.get(e,"fxshow");for(r in n.queue||(null==(a=k._queueHooks(e,"fx")).unqueued&&(a.unqueued=0,s=a.empty.fire,a.empty.fire=function(){a.unqueued||s()}),a.unqueued++,p.always(function(){p.always(function(){a.unqueued--,k.queue(e,"fx").length||a.empty.fire()})})),t)if(i=t[r],st.test(i)){if(delete t[r],o=o||"toggle"===i,i===(g?"hide":"show")){if("show"!==i||!v||void 0===v[r])continue;g=!0}d[r]=v&&v[r]||k.style(e,r)}if((u=!k.isEmptyObject(t))||!k.isEmptyObject(d))for(r in f&&1===e.nodeType&&(n.overflow=[h.overflow,h.overflowX,h.overflowY],null==(l=v&&v.display)&&(l=Q.get(e,"display")),"none"===(c=k.css(e,"display"))&&(l?c=l:(fe([e],!0),l=e.style.display||l,c=k.css(e,"display"),fe([e]))),("inline"===c||"inline-block"===c&&null!=l)&&"none"===k.css(e,"float")&&(u||(p.done(function(){h.display=l}),null==l&&(c=h.display,l="none"===c?"":c)),h.display="inline-block")),n.overflow&&(h.overflow="hidden",p.always(function(){h.overflow=n.overflow[0],h.overflowX=n.overflow[1],h.overflowY=n.overflow[2]})),u=!1,d)u||(v?"hidden"in v&&(g=v.hidden):v=Q.access(e,"fxshow",{display:l}),o&&(v.hidden=!g),g&&fe([e],!0),p.done(function(){for(r in g||fe([e]),Q.remove(e,"fxshow"),d)k.style(e,r,d[r])})),u=pt(g?v[r]:0,r,p),r in v||(v[r]=u.start,g&&(u.end=u.start,u.start=0))}],prefilter:function(e,t){t?dt.prefilters.unshift(e):dt.prefilters.push(e)}}),k.speed=function(e,t,n){var r=e&&"object"==typeof e?k.extend({},e):{complete:n||!n&&t||m(e)&&e,duration:e,easing:n&&t||t&&!m(t)&&t};return k.fx.off?r.duration=0:"number"!=typeof r.duration&&(r.duration in k.fx.speeds?r.duration=k.fx.speeds[r.duration]:r.duration=k.fx.speeds._default),null!=r.queue&&!0!==r.queue||(r.queue="fx"),r.old=r.complete,r.complete=function(){m(r.old)&&r.old.call(this),r.queue&&k.dequeue(this,r.queue)},r},k.fn.extend({fadeTo:function(e,t,n,r){return this.filter(se).css("opacity",0).show().end().animate({opacity:t},e,n,r)},animate:function(t,e,n,r){var i=k.isEmptyObject(t),o=k.speed(e,n,r),a=function(){var e=dt(this,k.extend({},t),o);(i||Q.get(this,"finish"))&&e.stop(!0)};return a.finish=a,i||!1===o.queue?this.each(a):this.queue(o.queue,a)},stop:function(i,e,o){var a=function(e){var t=e.stop;delete e.stop,t(o)};return"string"!=typeof i&&(o=e,e=i,i=void 0),e&&!1!==i&&this.queue(i||"fx",[]),this.each(function(){var e=!0,t=null!=i&&i+"queueHooks",n=k.timers,r=Q.get(this);if(t)r[t]&&r[t].stop&&a(r[t]);else for(t in r)r[t]&&r[t].stop&&ut.test(t)&&a(r[t]);for(t=n.length;t--;)n[t].elem!==this||null!=i&&n[t].queue!==i||(n[t].anim.stop(o),e=!1,n.splice(t,1));!e&&o||k.dequeue(this,i)})},finish:function(a){return!1!==a&&(a=a||"fx"),this.each(function(){var e,t=Q.get(this),n=t[a+"queue"],r=t[a+"queueHooks"],i=k.timers,o=n?n.length:0;for(t.finish=!0,k.queue(this,a,[]),r&&r.stop&&r.stop.call(this,!0),e=i.length;e--;)i[e].elem===this&&i[e].queue===a&&(i[e].anim.stop(!0),i.splice(e,1));for(e=0;e<o;e++)n[e]&&n[e].finish&&n[e].finish.call(this);delete t.finish})}}),k.each(["toggle","show","hide"],function(e,r){var i=k.fn[r];k.fn[r]=function(e,t,n){return null==e||"boolean"==typeof e?i.apply(this,arguments):this.animate(ft(r,!0),e,t,n)}}),k.each({slideDown:ft("show"),slideUp:ft("hide"),slideToggle:ft("toggle"),fadeIn:{opacity:"show"},fadeOut:{opacity:"hide"},fadeToggle:{opacity:"toggle"}},function(e,r){k.fn[e]=function(e,t,n){return this.animate(r,e,t,n)}}),k.timers=[],k.fx.tick=function(){var e,t=0,n=k.timers;for(rt=Date.now();t<n.length;t++)(e=n[t])()||n[t]!==e||n.splice(t--,1);n.length||k.fx.stop(),rt=void 0},k.fx.timer=function(e){k.timers.push(e),k.fx.start()},k.fx.interval=13,k.fx.start=function(){it||(it=!0,lt())},k.fx.stop=function(){it=null},k.fx.speeds={slow:600,fast:200,_default:400},k.fn.delay=function(r,e){return r=k.fx&&k.fx.speeds[r]||r,e=e||"fx",this.queue(e,function(e,t){var n=C.setTimeout(e,r);t.stop=function(){C.clearTimeout(n)}})},ot=E.createElement("input"),at=E.createElement("select").appendChild(E.createElement("option")),ot.type="checkbox",y.checkOn=""!==ot.value,y.optSelected=at.selected,(ot=E.createElement("input")).value="t",ot.type="radio",y.radioValue="t"===ot.value;var ht,gt=k.expr.attrHandle;k.fn.extend({attr:function(e,t){return _(this,k.attr,e,t,1<arguments.length)},removeAttr:function(e){return this.each(function(){k.removeAttr(this,e)})}}),k.extend({attr:function(e,t,n){var r,i,o=e.nodeType;if(3!==o&&8!==o&&2!==o)return"undefined"==typeof e.getAttribute?k.prop(e,t,n):(1===o&&k.isXMLDoc(e)||(i=k.attrHooks[t.toLowerCase()]||(k.expr.match.bool.test(t)?ht:void 0)),void 0!==n?null===n?void k.removeAttr(e,t):i&&"set"in i&&void 0!==(r=i.set(e,n,t))?r:(e.setAttribute(t,n+""),n):i&&"get"in i&&null!==(r=i.get(e,t))?r:null==(r=k.find.attr(e,t))?void 0:r)},attrHooks:{type:{set:function(e,t){if(!y.radioValue&&"radio"===t&&A(e,"input")){var n=e.value;return e.setAttribute("type",t),n&&(e.value=n),t}}}},removeAttr:function(e,t){var n,r=0,i=t&&t.match(R);if(i&&1===e.nodeType)while(n=i[r++])e.removeAttribute(n)}}),ht={set:function(e,t,n){return!1===t?k.removeAttr(e,n):e.setAttribute(n,n),n}},k.each(k.expr.match.bool.source.match(/\w+/g),function(e,t){var a=gt[t]||k.find.attr;gt[t]=function(e,t,n){var r,i,o=t.toLowerCase();return n||(i=gt[o],gt[o]=r,r=null!=a(e,t,n)?o:null,gt[o]=i),r}});var vt=/^(?:input|select|textarea|button)$/i,yt=/^(?:a|area)$/i;function mt(e){return(e.match(R)||[]).join(" ")}function xt(e){return e.getAttribute&&e.getAttribute("class")||""}function bt(e){return Array.isArray(e)?e:"string"==typeof e&&e.match(R)||[]}k.fn.extend({prop:function(e,t){return _(this,k.prop,e,t,1<arguments.length)},removeProp:function(e){return this.each(function(){delete this[k.propFix[e]||e]})}}),k.extend({prop:function(e,t,n){var r,i,o=e.nodeType;if(3!==o&&8!==o&&2!==o)return 1===o&&k.isXMLDoc(e)||(t=k.propFix[t]||t,i=k.propHooks[t]),void 0!==n?i&&"set"in i&&void 0!==(r=i.set(e,n,t))?r:e[t]=n:i&&"get"in i&&null!==(r=i.get(e,t))?r:e[t]},propHooks:{tabIndex:{get:function(e){var t=k.find.attr(e,"tabindex");return t?parseInt(t,10):vt.test(e.nodeName)||yt.test(e.nodeName)&&e.href?0:-1}}},propFix:{"for":"htmlFor","class":"className"}}),y.optSelected||(k.propHooks.selected={get:function(e){var t=e.parentNode;return t&&t.parentNode&&t.parentNode.selectedIndex,null},set:function(e){var t=e.parentNode;t&&(t.selectedIndex,t.parentNode&&t.parentNode.selectedIndex)}}),k.each(["tabIndex","readOnly","maxLength","cellSpacing","cellPadding","rowSpan","colSpan","useMap","frameBorder","contentEditable"],function(){k.propFix[this.toLowerCase()]=this}),k.fn.extend({addClass:function(t){var e,n,r,i,o,a,s,u=0;if(m(t))return this.each(function(e){k(this).addClass(t.call(this,e,xt(this)))});if((e=bt(t)).length)while(n=this[u++])if(i=xt(n),r=1===n.nodeType&&" "+mt(i)+" "){a=0;while(o=e[a++])r.indexOf(" "+o+" ")<0&&(r+=o+" ");i!==(s=mt(r))&&n.setAttribute("class",s)}return this},removeClass:function(t){var e,n,r,i,o,a,s,u=0;if(m(t))return this.each(function(e){k(this).removeClass(t.call(this,e,xt(this)))});if(!arguments.length)return this.attr("class","");if((e=bt(t)).length)while(n=this[u++])if(i=xt(n),r=1===n.nodeType&&" "+mt(i)+" "){a=0;while(o=e[a++])while(-1<r.indexOf(" "+o+" "))r=r.replace(" "+o+" "," ");i!==(s=mt(r))&&n.setAttribute("class",s)}return this},toggleClass:function(i,t){var o=typeof i,a="string"===o||Array.isArray(i);return"boolean"==typeof t&&a?t?this.addClass(i):this.removeClass(i):m(i)?this.each(function(e){k(this).toggleClass(i.call(this,e,xt(this),t),t)}):this.each(function(){var e,t,n,r;if(a){t=0,n=k(this),r=bt(i);while(e=r[t++])n.hasClass(e)?n.removeClass(e):n.addClass(e)}else void 0!==i&&"boolean"!==o||((e=xt(this))&&Q.set(this,"__className__",e),this.setAttribute&&this.setAttribute("class",e||!1===i?"":Q.get(this,"__className__")||""))})},hasClass:function(e){var t,n,r=0;t=" "+e+" ";while(n=this[r++])if(1===n.nodeType&&-1<(" "+mt(xt(n))+" ").indexOf(t))return!0;return!1}});var wt=/\r/g;k.fn.extend({val:function(n){var r,e,i,t=this[0];return arguments.length?(i=m(n),this.each(function(e){var t;1===this.nodeType&&(null==(t=i?n.call(this,e,k(this).val()):n)?t="":"number"==typeof t?t+="":Array.isArray(t)&&(t=k.map(t,function(e){return null==e?"":e+""})),(r=k.valHooks[this.type]||k.valHooks[this.nodeName.toLowerCase()])&&"set"in r&&void 0!==r.set(this,t,"value")||(this.value=t))})):t?(r=k.valHooks[t.type]||k.valHooks[t.nodeName.toLowerCase()])&&"get"in r&&void 0!==(e=r.get(t,"value"))?e:"string"==typeof(e=t.value)?e.replace(wt,""):null==e?"":e:void 0}}),k.extend({valHooks:{option:{get:function(e){var t=k.find.attr(e,"value");return null!=t?t:mt(k.text(e))}},select:{get:function(e){var t,n,r,i=e.options,o=e.selectedIndex,a="select-one"===e.type,s=a?null:[],u=a?o+1:i.length;for(r=o<0?u:a?o:0;r<u;r++)if(((n=i[r]).selected||r===o)&&!n.disabled&&(!n.parentNode.disabled||!A(n.parentNode,"optgroup"))){if(t=k(n).val(),a)return t;s.push(t)}return s},set:function(e,t){var n,r,i=e.options,o=k.makeArray(t),a=i.length;while(a--)((r=i[a]).selected=-1<k.inArray(k.valHooks.option.get(r),o))&&(n=!0);return n||(e.selectedIndex=-1),o}}}}),k.each(["radio","checkbox"],function(){k.valHooks[this]={set:function(e,t){if(Array.isArray(t))return e.checked=-1<k.inArray(k(e).val(),t)}},y.checkOn||(k.valHooks[this].get=function(e){return null===e.getAttribute("value")?"on":e.value})}),y.focusin="onfocusin"in C;var Tt=/^(?:focusinfocus|focusoutblur)$/,Ct=function(e){e.stopPropagation()};k.extend(k.event,{trigger:function(e,t,n,r){var i,o,a,s,u,l,c,f,p=[n||E],d=v.call(e,"type")?e.type:e,h=v.call(e,"namespace")?e.namespace.split("."):[];if(o=f=a=n=n||E,3!==n.nodeType&&8!==n.nodeType&&!Tt.test(d+k.event.triggered)&&(-1<d.indexOf(".")&&(d=(h=d.split(".")).shift(),h.sort()),u=d.indexOf(":")<0&&"on"+d,(e=e[k.expando]?e:new k.Event(d,"object"==typeof e&&e)).isTrigger=r?2:3,e.namespace=h.join("."),e.rnamespace=e.namespace?new RegExp("(^|\\.)"+h.join("\\.(?:.*\\.|)")+"(\\.|$)"):null,e.result=void 0,e.target||(e.target=n),t=null==t?[e]:k.makeArray(t,[e]),c=k.event.special[d]||{},r||!c.trigger||!1!==c.trigger.apply(n,t))){if(!r&&!c.noBubble&&!x(n)){for(s=c.delegateType||d,Tt.test(s+d)||(o=o.parentNode);o;o=o.parentNode)p.push(o),a=o;a===(n.ownerDocument||E)&&p.push(a.defaultView||a.parentWindow||C)}i=0;while((o=p[i++])&&!e.isPropagationStopped())f=o,e.type=1<i?s:c.bindType||d,(l=(Q.get(o,"events")||{})[e.type]&&Q.get(o,"handle"))&&l.apply(o,t),(l=u&&o[u])&&l.apply&&G(o)&&(e.result=l.apply(o,t),!1===e.result&&e.preventDefault());return e.type=d,r||e.isDefaultPrevented()||c._default&&!1!==c._default.apply(p.pop(),t)||!G(n)||u&&m(n[d])&&!x(n)&&((a=n[u])&&(n[u]=null),k.event.triggered=d,e.isPropagationStopped()&&f.addEventListener(d,Ct),n[d](),e.isPropagationStopped()&&f.removeEventListener(d,Ct),k.event.triggered=void 0,a&&(n[u]=a)),e.result}},simulate:function(e,t,n){var r=k.extend(new k.Event,n,{type:e,isSimulated:!0});k.event.trigger(r,null,t)}}),k.fn.extend({trigger:function(e,t){return this.each(function(){k.event.trigger(e,t,this)})},triggerHandler:function(e,t){var n=this[0];if(n)return k.event.trigger(e,t,n,!0)}}),y.focusin||k.each({focus:"focusin",blur:"focusout"},function(n,r){var i=function(e){k.event.simulate(r,e.target,k.event.fix(e))};k.event.special[r]={setup:function(){var e=this.ownerDocument||this,t=Q.access(e,r);t||e.addEventListener(n,i,!0),Q.access(e,r,(t||0)+1)},teardown:function(){var e=this.ownerDocument||this,t=Q.access(e,r)-1;t?Q.access(e,r,t):(e.removeEventListener(n,i,!0),Q.remove(e,r))}}});var Et=C.location,kt=Date.now(),St=/\?/;k.parseXML=function(e){var t;if(!e||"string"!=typeof e)return null;try{t=(new C.DOMParser).parseFromString(e,"text/xml")}catch(e){t=void 0}return t&&!t.getElementsByTagName("parsererror").length||k.error("Invalid XML: "+e),t};var Nt=/\[\]$/,At=/\r?\n/g,Dt=/^(?:submit|button|image|reset|file)$/i,jt=/^(?:input|select|textarea|keygen)/i;function qt(n,e,r,i){var t;if(Array.isArray(e))k.each(e,function(e,t){r||Nt.test(n)?i(n,t):qt(n+"["+("object"==typeof t&&null!=t?e:"")+"]",t,r,i)});else if(r||"object"!==w(e))i(n,e);else for(t in e)qt(n+"["+t+"]",e[t],r,i)}k.param=function(e,t){var n,r=[],i=function(e,t){var n=m(t)?t():t;r[r.length]=encodeURIComponent(e)+"="+encodeURIComponent(null==n?"":n)};if(null==e)return"";if(Array.isArray(e)||e.jquery&&!k.isPlainObject(e))k.each(e,function(){i(this.name,this.value)});else for(n in e)qt(n,e[n],t,i);return r.join("&")},k.fn.extend({serialize:function(){return k.param(this.serializeArray())},serializeArray:function(){return this.map(function(){var e=k.prop(this,"elements");return e?k.makeArray(e):this}).filter(function(){var e=this.type;return this.name&&!k(this).is(":disabled")&&jt.test(this.nodeName)&&!Dt.test(e)&&(this.checked||!pe.test(e))}).map(function(e,t){var n=k(this).val();return null==n?null:Array.isArray(n)?k.map(n,function(e){return{name:t.name,value:e.replace(At,"\r\n")}}):{name:t.name,value:n.replace(At,"\r\n")}}).get()}});var Lt=/%20/g,Ht=/#.*$/,Ot=/([?&])_=[^&]*/,Pt=/^(.*?):[ \t]*([^\r\n]*)$/gm,Rt=/^(?:GET|HEAD)$/,Mt=/^\/\//,It={},Wt={},$t="*/".concat("*"),Ft=E.createElement("a");function Bt(o){return function(e,t){"string"!=typeof e&&(t=e,e="*");var n,r=0,i=e.toLowerCase().match(R)||[];if(m(t))while(n=i[r++])"+"===n[0]?(n=n.slice(1)||"*",(o[n]=o[n]||[]).unshift(t)):(o[n]=o[n]||[]).push(t)}}function _t(t,i,o,a){var s={},u=t===Wt;function l(e){var r;return s[e]=!0,k.each(t[e]||[],function(e,t){var n=t(i,o,a);return"string"!=typeof n||u||s[n]?u?!(r=n):void 0:(i.dataTypes.unshift(n),l(n),!1)}),r}return l(i.dataTypes[0])||!s["*"]&&l("*")}function zt(e,t){var n,r,i=k.ajaxSettings.flatOptions||{};for(n in t)void 0!==t[n]&&((i[n]?e:r||(r={}))[n]=t[n]);return r&&k.extend(!0,e,r),e}Ft.href=Et.href,k.extend({active:0,lastModified:{},etag:{},ajaxSettings:{url:Et.href,type:"GET",isLocal:/^(?:about|app|app-storage|.+-extension|file|res|widget):$/.test(Et.protocol),global:!0,processData:!0,async:!0,contentType:"application/x-www-form-urlencoded; charset=UTF-8",accepts:{"*":$t,text:"text/plain",html:"text/html",xml:"application/xml, text/xml",json:"application/json, text/javascript"},contents:{xml:/\bxml\b/,html:/\bhtml/,json:/\bjson\b/},responseFields:{xml:"responseXML",text:"responseText",json:"responseJSON"},converters:{"* text":String,"text html":!0,"text json":JSON.parse,"text xml":k.parseXML},flatOptions:{url:!0,context:!0}},ajaxSetup:function(e,t){return t?zt(zt(e,k.ajaxSettings),t):zt(k.ajaxSettings,e)},ajaxPrefilter:Bt(It),ajaxTransport:Bt(Wt),ajax:function(e,t){"object"==typeof e&&(t=e,e=void 0),t=t||{};var c,f,p,n,d,r,h,g,i,o,v=k.ajaxSetup({},t),y=v.context||v,m=v.context&&(y.nodeType||y.jquery)?k(y):k.event,x=k.Deferred(),b=k.Callbacks("once memory"),w=v.statusCode||{},a={},s={},u="canceled",T={readyState:0,getResponseHeader:function(e){var t;if(h){if(!n){n={};while(t=Pt.exec(p))n[t[1].toLowerCase()+" "]=(n[t[1].toLowerCase()+" "]||[]).concat(t[2])}t=n[e.toLowerCase()+" "]}return null==t?null:t.join(", ")},getAllResponseHeaders:function(){return h?p:null},setRequestHeader:function(e,t){return null==h&&(e=s[e.toLowerCase()]=s[e.toLowerCase()]||e,a[e]=t),this},overrideMimeType:function(e){return null==h&&(v.mimeType=e),this},statusCode:function(e){var t;if(e)if(h)T.always(e[T.status]);else for(t in e)w[t]=[w[t],e[t]];return this},abort:function(e){var t=e||u;return c&&c.abort(t),l(0,t),this}};if(x.promise(T),v.url=((e||v.url||Et.href)+"").replace(Mt,Et.protocol+"//"),v.type=t.method||t.type||v.method||v.type,v.dataTypes=(v.dataType||"*").toLowerCase().match(R)||[""],null==v.crossDomain){r=E.createElement("a");try{r.href=v.url,r.href=r.href,v.crossDomain=Ft.protocol+"//"+Ft.host!=r.protocol+"//"+r.host}catch(e){v.crossDomain=!0}}if(v.data&&v.processData&&"string"!=typeof v.data&&(v.data=k.param(v.data,v.traditional)),_t(It,v,t,T),h)return T;for(i in(g=k.event&&v.global)&&0==k.active++&&k.event.trigger("ajaxStart"),v.type=v.type.toUpperCase(),v.hasContent=!Rt.test(v.type),f=v.url.replace(Ht,""),v.hasContent?v.data&&v.processData&&0===(v.contentType||"").indexOf("application/x-www-form-urlencoded")&&(v.data=v.data.replace(Lt,"+")):(o=v.url.slice(f.length),v.data&&(v.processData||"string"==typeof v.data)&&(f+=(St.test(f)?"&":"?")+v.data,delete v.data),!1===v.cache&&(f=f.replace(Ot,"$1"),o=(St.test(f)?"&":"?")+"_="+kt+++o),v.url=f+o),v.ifModified&&(k.lastModified[f]&&T.setRequestHeader("If-Modified-Since",k.lastModified[f]),k.etag[f]&&T.setRequestHeader("If-None-Match",k.etag[f])),(v.data&&v.hasContent&&!1!==v.contentType||t.contentType)&&T.setRequestHeader("Content-Type",v.contentType),T.setRequestHeader("Accept",v.dataTypes[0]&&v.accepts[v.dataTypes[0]]?v.accepts[v.dataTypes[0]]+("*"!==v.dataTypes[0]?", "+$t+"; q=0.01":""):v.accepts["*"]),v.headers)T.setRequestHeader(i,v.headers[i]);if(v.beforeSend&&(!1===v.beforeSend.call(y,T,v)||h))return T.abort();if(u="abort",b.add(v.complete),T.done(v.success),T.fail(v.error),c=_t(Wt,v,t,T)){if(T.readyState=1,g&&m.trigger("ajaxSend",[T,v]),h)return T;v.async&&0<v.timeout&&(d=C.setTimeout(function(){T.abort("timeout")},v.timeout));try{h=!1,c.send(a,l)}catch(e){if(h)throw e;l(-1,e)}}else l(-1,"No Transport");function l(e,t,n,r){var i,o,a,s,u,l=t;h||(h=!0,d&&C.clearTimeout(d),c=void 0,p=r||"",T.readyState=0<e?4:0,i=200<=e&&e<300||304===e,n&&(s=function(e,t,n){var r,i,o,a,s=e.contents,u=e.dataTypes;while("*"===u[0])u.shift(),void 0===r&&(r=e.mimeType||t.getResponseHeader("Content-Type"));if(r)for(i in s)if(s[i]&&s[i].test(r)){u.unshift(i);break}if(u[0]in n)o=u[0];else{for(i in n){if(!u[0]||e.converters[i+" "+u[0]]){o=i;break}a||(a=i)}o=o||a}if(o)return o!==u[0]&&u.unshift(o),n[o]}(v,T,n)),s=function(e,t,n,r){var i,o,a,s,u,l={},c=e.dataTypes.slice();if(c[1])for(a in e.converters)l[a.toLowerCase()]=e.converters[a];o=c.shift();while(o)if(e.responseFields[o]&&(n[e.responseFields[o]]=t),!u&&r&&e.dataFilter&&(t=e.dataFilter(t,e.dataType)),u=o,o=c.shift())if("*"===o)o=u;else if("*"!==u&&u!==o){if(!(a=l[u+" "+o]||l["* "+o]))for(i in l)if((s=i.split(" "))[1]===o&&(a=l[u+" "+s[0]]||l["* "+s[0]])){!0===a?a=l[i]:!0!==l[i]&&(o=s[0],c.unshift(s[1]));break}if(!0!==a)if(a&&e["throws"])t=a(t);else try{t=a(t)}catch(e){return{state:"parsererror",error:a?e:"No conversion from "+u+" to "+o}}}return{state:"success",data:t}}(v,s,T,i),i?(v.ifModified&&((u=T.getResponseHeader("Last-Modified"))&&(k.lastModified[f]=u),(u=T.getResponseHeader("etag"))&&(k.etag[f]=u)),204===e||"HEAD"===v.type?l="nocontent":304===e?l="notmodified":(l=s.state,o=s.data,i=!(a=s.error))):(a=l,!e&&l||(l="error",e<0&&(e=0))),T.status=e,T.statusText=(t||l)+"",i?x.resolveWith(y,[o,l,T]):x.rejectWith(y,[T,l,a]),T.statusCode(w),w=void 0,g&&m.trigger(i?"ajaxSuccess":"ajaxError",[T,v,i?o:a]),b.fireWith(y,[T,l]),g&&(m.trigger("ajaxComplete",[T,v]),--k.active||k.event.trigger("ajaxStop")))}return T},getJSON:function(e,t,n){return k.get(e,t,n,"json")},getScript:function(e,t){return k.get(e,void 0,t,"script")}}),k.each(["get","post"],function(e,i){k[i]=function(e,t,n,r){return m(t)&&(r=r||n,n=t,t=void 0),k.ajax(k.extend({url:e,type:i,dataType:r,data:t,success:n},k.isPlainObject(e)&&e))}}),k._evalUrl=function(e,t){return k.ajax({url:e,type:"GET",dataType:"script",cache:!0,async:!1,global:!1,converters:{"text script":function(){}},dataFilter:function(e){k.globalEval(e,t)}})},k.fn.extend({wrapAll:function(e){var t;return this[0]&&(m(e)&&(e=e.call(this[0])),t=k(e,this[0].ownerDocument).eq(0).clone(!0),this[0].parentNode&&t.insertBefore(this[0]),t.map(function(){var e=this;while(e.firstElementChild)e=e.firstElementChild;return e}).append(this)),this},wrapInner:function(n){return m(n)?this.each(function(e){k(this).wrapInner(n.call(this,e))}):this.each(function(){var e=k(this),t=e.contents();t.length?t.wrapAll(n):e.append(n)})},wrap:function(t){var n=m(t);return this.each(function(e){k(this).wrapAll(n?t.call(this,e):t)})},unwrap:function(e){return this.parent(e).not("body").each(function(){k(this).replaceWith(this.childNodes)}),this}}),k.expr.pseudos.hidden=function(e){return!k.expr.pseudos.visible(e)},k.expr.pseudos.visible=function(e){return!!(e.offsetWidth||e.offsetHeight||e.getClientRects().length)},k.ajaxSettings.xhr=function(){try{return new C.XMLHttpRequest}catch(e){}};var Ut={0:200,1223:204},Xt=k.ajaxSettings.xhr();y.cors=!!Xt&&"withCredentials"in Xt,y.ajax=Xt=!!Xt,k.ajaxTransport(function(i){var o,a;if(y.cors||Xt&&!i.crossDomain)return{send:function(e,t){var n,r=i.xhr();if(r.open(i.type,i.url,i.async,i.username,i.password),i.xhrFields)for(n in i.xhrFields)r[n]=i.xhrFields[n];for(n in i.mimeType&&r.overrideMimeType&&r.overrideMimeType(i.mimeType),i.crossDomain||e["X-Requested-With"]||(e["X-Requested-With"]="XMLHttpRequest"),e)r.setRequestHeader(n,e[n]);o=function(e){return function(){o&&(o=a=r.onload=r.onerror=r.onabort=r.ontimeout=r.onreadystatechange=null,"abort"===e?r.abort():"error"===e?"number"!=typeof r.status?t(0,"error"):t(r.status,r.statusText):t(Ut[r.status]||r.status,r.statusText,"text"!==(r.responseType||"text")||"string"!=typeof r.responseText?{binary:r.response}:{text:r.responseText},r.getAllResponseHeaders()))}},r.onload=o(),a=r.onerror=r.ontimeout=o("error"),void 0!==r.onabort?r.onabort=a:r.onreadystatechange=function(){4===r.readyState&&C.setTimeout(function(){o&&a()})},o=o("abort");try{r.send(i.hasContent&&i.data||null)}catch(e){if(o)throw e}},abort:function(){o&&o()}}}),k.ajaxPrefilter(function(e){e.crossDomain&&(e.contents.script=!1)}),k.ajaxSetup({accepts:{script:"text/javascript, application/javascript, application/ecmascript, application/x-ecmascript"},contents:{script:/\b(?:java|ecma)script\b/},converters:{"text script":function(e){return k.globalEval(e),e}}}),k.ajaxPrefilter("script",function(e){void 0===e.cache&&(e.cache=!1),e.crossDomain&&(e.type="GET")}),k.ajaxTransport("script",function(n){var r,i;if(n.crossDomain||n.scriptAttrs)return{send:function(e,t){r=k("<script>").attr(n.scriptAttrs||{}).prop({charset:n.scriptCharset,src:n.url}).on("load error",i=function(e){r.remove(),i=null,e&&t("error"===e.type?404:200,e.type)}),E.head.appendChild(r[0])},abort:function(){i&&i()}}});var Vt,Gt=[],Yt=/(=)\?(?=&|$)|\?\?/;k.ajaxSetup({jsonp:"callback",jsonpCallback:function(){var e=Gt.pop()||k.expando+"_"+kt++;return this[e]=!0,e}}),k.ajaxPrefilter("json jsonp",function(e,t,n){var r,i,o,a=!1!==e.jsonp&&(Yt.test(e.url)?"url":"string"==typeof e.data&&0===(e.contentType||"").indexOf("application/x-www-form-urlencoded")&&Yt.test(e.data)&&"data");if(a||"jsonp"===e.dataTypes[0])return r=e.jsonpCallback=m(e.jsonpCallback)?e.jsonpCallback():e.jsonpCallback,a?e[a]=e[a].replace(Yt,"$1"+r):!1!==e.jsonp&&(e.url+=(St.test(e.url)?"&":"?")+e.jsonp+"="+r),e.converters["script json"]=function(){return o||k.error(r+" was not called"),o[0]},e.dataTypes[0]="json",i=C[r],C[r]=function(){o=arguments},n.always(function(){void 0===i?k(C).removeProp(r):C[r]=i,e[r]&&(e.jsonpCallback=t.jsonpCallback,Gt.push(r)),o&&m(i)&&i(o[0]),o=i=void 0}),"script"}),y.createHTMLDocument=((Vt=E.implementation.createHTMLDocument("").body).innerHTML="<form></form><form></form>",2===Vt.childNodes.length),k.parseHTML=function(e,t,n){return"string"!=typeof e?[]:("boolean"==typeof t&&(n=t,t=!1),t||(y.createHTMLDocument?((r=(t=E.implementation.createHTMLDocument("")).createElement("base")).href=E.location.href,t.head.appendChild(r)):t=E),o=!n&&[],(i=D.exec(e))?[t.createElement(i[1])]:(i=we([e],t,o),o&&o.length&&k(o).remove(),k.merge([],i.childNodes)));var r,i,o},k.fn.load=function(e,t,n){var r,i,o,a=this,s=e.indexOf(" ");return-1<s&&(r=mt(e.slice(s)),e=e.slice(0,s)),m(t)?(n=t,t=void 0):t&&"object"==typeof t&&(i="POST"),0<a.length&&k.ajax({url:e,type:i||"GET",dataType:"html",data:t}).done(function(e){o=arguments,a.html(r?k("<div>").append(k.parseHTML(e)).find(r):e)}).always(n&&function(e,t){a.each(function(){n.apply(this,o||[e.responseText,t,e])})}),this},k.each(["ajaxStart","ajaxStop","ajaxComplete","ajaxError","ajaxSuccess","ajaxSend"],function(e,t){k.fn[t]=function(e){return this.on(t,e)}}),k.expr.pseudos.animated=function(t){return k.grep(k.timers,function(e){return t===e.elem}).length},k.offset={setOffset:function(e,t,n){var r,i,o,a,s,u,l=k.css(e,"position"),c=k(e),f={};"static"===l&&(e.style.position="relative"),s=c.offset(),o=k.css(e,"top"),u=k.css(e,"left"),("absolute"===l||"fixed"===l)&&-1<(o+u).indexOf("auto")?(a=(r=c.position()).top,i=r.left):(a=parseFloat(o)||0,i=parseFloat(u)||0),m(t)&&(t=t.call(e,n,k.extend({},s))),null!=t.top&&(f.top=t.top-s.top+a),null!=t.left&&(f.left=t.left-s.left+i),"using"in t?t.using.call(e,f):c.css(f)}},k.fn.extend({offset:function(t){if(arguments.length)return void 0===t?this:this.each(function(e){k.offset.setOffset(this,t,e)});var e,n,r=this[0];return r?r.getClientRects().length?(e=r.getBoundingClientRect(),n=r.ownerDocument.defaultView,{top:e.top+n.pageYOffset,left:e.left+n.pageXOffset}):{top:0,left:0}:void 0},position:function(){if(this[0]){var e,t,n,r=this[0],i={top:0,left:0};if("fixed"===k.css(r,"position"))t=r.getBoundingClientRect();else{t=this.offset(),n=r.ownerDocument,e=r.offsetParent||n.documentElement;while(e&&(e===n.body||e===n.documentElement)&&"static"===k.css(e,"position"))e=e.parentNode;e&&e!==r&&1===e.nodeType&&((i=k(e).offset()).top+=k.css(e,"borderTopWidth",!0),i.left+=k.css(e,"borderLeftWidth",!0))}return{top:t.top-i.top-k.css(r,"marginTop",!0),left:t.left-i.left-k.css(r,"marginLeft",!0)}}},offsetParent:function(){return this.map(function(){var e=this.offsetParent;while(e&&"static"===k.css(e,"position"))e=e.offsetParent;return e||ie})}}),k.each({scrollLeft:"pageXOffset",scrollTop:"pageYOffset"},function(t,i){var o="pageYOffset"===i;k.fn[t]=function(e){return _(this,function(e,t,n){var r;if(x(e)?r=e:9===e.nodeType&&(r=e.defaultView),void 0===n)return r?r[i]:e[t];r?r.scrollTo(o?r.pageXOffset:n,o?n:r.pageYOffset):e[t]=n},t,e,arguments.length)}}),k.each(["top","left"],function(e,n){k.cssHooks[n]=ze(y.pixelPosition,function(e,t){if(t)return t=_e(e,n),$e.test(t)?k(e).position()[n]+"px":t})}),k.each({Height:"height",Width:"width"},function(a,s){k.each({padding:"inner"+a,content:s,"":"outer"+a},function(r,o){k.fn[o]=function(e,t){var n=arguments.length&&(r||"boolean"!=typeof e),i=r||(!0===e||!0===t?"margin":"border");return _(this,function(e,t,n){var r;return x(e)?0===o.indexOf("outer")?e["inner"+a]:e.document.documentElement["client"+a]:9===e.nodeType?(r=e.documentElement,Math.max(e.body["scroll"+a],r["scroll"+a],e.body["offset"+a],r["offset"+a],r["client"+a])):void 0===n?k.css(e,t,i):k.style(e,t,n,i)},s,n?e:void 0,n)}})}),k.each("blur focus focusin focusout resize scroll click dblclick mousedown mouseup mousemove mouseover mouseout mouseenter mouseleave change select submit keydown keypress keyup contextmenu".split(" "),function(e,n){k.fn[n]=function(e,t){return 0<arguments.length?this.on(n,null,e,t):this.trigger(n)}}),k.fn.extend({hover:function(e,t){return this.mouseenter(e).mouseleave(t||e)}}),k.fn.extend({bind:function(e,t,n){return this.on(e,null,t,n)},unbind:function(e,t){return this.off(e,null,t)},delegate:function(e,t,n,r){return this.on(t,e,n,r)},undelegate:function(e,t,n){return 1===arguments.length?this.off(e,"**"):this.off(t,e||"**",n)}}),k.proxy=function(e,t){var n,r,i;if("string"==typeof t&&(n=e[t],t=e,e=n),m(e))return r=s.call(arguments,2),(i=function(){return e.apply(t||this,r.concat(s.call(arguments)))}).guid=e.guid=e.guid||k.guid++,i},k.holdReady=function(e){e?k.readyWait++:k.ready(!0)},k.isArray=Array.isArray,k.parseJSON=JSON.parse,k.nodeName=A,k.isFunction=m,k.isWindow=x,k.camelCase=V,k.type=w,k.now=Date.now,k.isNumeric=function(e){var t=k.type(e);return("number"===t||"string"===t)&&!isNaN(e-parseFloat(e))},"function"==typeof define&&define.amd&&define("jquery",[],function(){return k});var Qt=C.jQuery,Jt=C.$;return k.noConflict=function(e){return C.$===k&&(C.$=Jt),e&&C.jQuery===k&&(C.jQuery=Qt),k},e||(C.jQuery=C.$=k),k}); </script>
            <script> let g_snapped = "";
// let g_lastHovered = "";

function hideAllDetails()
{
    $(".container-feature-detail").hide();
    $(".container-df-associations").hide();
    $("span.bg-tab-summary-rollover").hide();
    $("#button-summary-associations-source, #button-summary-associations-compare").removeClass("button-assoc-selected");
    $("#button-summary-associations-source, #button-summary-associations-compare").addClass("button-assoc");
}


// GLOBAL EVENTS
// ---------------------------------------------------------------------------------------------------------------------------
// EVENT: [ANYWHERE] RIGHT-CLICK REMOVES SELECTION
// $(document).contextmenu(function() {
//     if (g_snapped != "")
//     {
//         g_snapped = "";
//         hideAllDetails();
//     }
//     if (g_lastHovered != "")
//     {
//         $(g_lastHovered).show();
//         //alert("#"+g_lastHovered);
//     }
//     return false;
// });

$("span.bg-tab-summary-rollover").hide();
hideAllDetails();

$(document).ready(function() {
// INITIALIZATION
// --------------------------------------------------------
hideAllDetails();
$("span.bg-tab-summary-rollover").hide();

// Make the detail column the same height, so the floating element has room
//$("#col2").height($("#col1").height());
$("#col1").height(g_height);
$("#col2").height(g_height);
//alert($("#col1").height());

// SUMMARY AREA
// --------------------------------------------------------
// EVENT: SUMMARY ROLLOVER
// $(".selector, .container-feature-summary-target").hover(
$(".selector").hover(
// ENTER function
function(event) {
    if(g_snapped=="")
    {
        // Rollover start!
        $(".container-feature-detail").hide();
        $("span.bg-tab-summary-rollover").hide();
        $("#" + $(this).data("detail-div")).show();
        $("#" + $(this).data("rollover-span")).removeClass("bg-tab-summary-rollover-locked");
        $("#" + $(this).data("rollover-span")).addClass("bg-tab-summary-rollover");
        $("#" + $(this).data("rollover-span")).show();
    }
    // g_lastHovered = "#" + $(this).data("detail-div");
    },
// EXIT function
function(event) {
    if(g_snapped=="")
    {
        // Rollover end!
        hideAllDetails();
//FBFB        $("#" + $(this).data("detail-div")).hide();
    }
    }
);
// EVENT: SUMMARY CLICK
// $(".container-feature-summary, .container-feature-summary-target").click(function(event) {
$(".selector").click(function(event) {
    // No matter what, we should deselect the associations buttons
    $("#button-summary-associations-source, #button-summary-associations-compare").removeClass("button-assoc-selected");
    $("#button-summary-associations-source, #button-summary-associations-compare").addClass("button-assoc");

    // alert($(this).parent().attr('id'));
    let this_to_snap=$(this).parent().attr('id');

    if(g_snapped == this_to_snap)
    {
        // "Unselect"
        $("#" + $(this).data("rollover-span")).removeClass("bg-tab-summary-rollover-locked");
        $("#" + $(this).data("rollover-span")).addClass("bg-tab-summary-rollover");
        g_snapped = "";
    }
    else if (g_snapped == "")
    {
        // "Select"
        $("#" + $(this).data("rollover-span")).removeClass("bg-tab-summary-rollover");
        $("#" + $(this).data("rollover-span")).addClass("bg-tab-summary-rollover-locked");
        g_snapped = $(this).parent().attr('id');
        //$("#" + $(this).data("detail-div")).show();
        //$(g_lastHovered).show();
        // alert(this.parent().id);
    }
    else if (g_snapped !== this_to_snap) // implied
    {
        // "Select" while another was previously selected
        $("#" + $("#"+g_snapped).children().data("rollover-span")).removeClass("bg-tab-summary-rollover-locked");
        $("#" + $("#"+g_snapped).children().data("rollover-span")).addClass("bg-tab-summary-rollover");

        $(".container-feature-detail").hide();
        $("span.bg-tab-summary-rollover").hide();
        $("#" + $(this).data("detail-div")).show();
        
        $("#" + $(this).data("rollover-span")).removeClass("bg-tab-summary-rollover");
        $("#" + $(this).data("rollover-span")).addClass("bg-tab-summary-rollover-locked");
        $("#" + $(this).data("rollover-span")).css("display","inline");
        g_snapped = $(this).parent().attr('id');
    }
/*
    if (g_snapped != "")
    {
        $('html,body').animate(
            {scrollTop: $("#" + g_snapped).offset().top},
            'fast');

    }

 */
}
);
/*
$(window).scroll(function(e){
  var $el = $('.container-feature-detail');
    $el.css({'position': 'fixed', 'top': '0px'});

});
function fix_scroll() {
  var s = parseFloat($(window).scrollTop()) / 0.6;
  var fixedTitle = $('.container-feature-detail');
  fixedTitle.css('position','absolute');
  fixedTitle.css('top',s + 'px');
}fix_scroll();

$(window).on('scroll',fix_scroll);
*/

// ---------------------------------------------------------------------------------------------------------------------------
// SPECIFIC BUTTONS
// ---------------------------------------------------------------------------------------------------------------------------
// SUMMARY: ASSOCIATIONS -> HOVER
// --------------------------------------------------------
$("#button-summary-associations-source, #button-summary-associations-compare").hover(
    // ENTER function
    function()
    {
        if(g_snapped=="")
        {
            hideAllDetails();
            $("#" + $(this).data("detail-div")).show();
            // $("#df-assoc").show();
            //$("#df-assoc").show();
        }
        // g_lastHovered = "#df-assoc";
    },
    // EXIT function
    function()
    {
        if(g_snapped=="")
        {
            hideAllDetails();
        }
    });

// SUMMARY: ASSOCIATIONS -> CLICK
// --------------------------------------------------------
$("#button-summary-associations-source, #button-summary-associations-compare").click(function(event) {
    // Quick hack: just remove the selected state to both buttons and restore if needed
    $("#button-summary-associations-source, #button-summary-associations-compare").removeClass("button-assoc-selected");
    $("#button-summary-associations-source, #button-summary-associations-compare").addClass("button-assoc");
    let this_to_snap=this.id;
    if(g_snapped == this_to_snap)
    {
        // DESELECT/HIDE ASSOC
        // --------------------------------------------------------
        g_snapped = "";
    }
    else if(g_snapped=="")
    {
        // SELECT/SHOW ASSOC (Hide other one if already shown)
        // --------------------------------------------------------
        //$(".container-feature-detail").hide();
        //alert("#" + this.id+" GS:"+g_snapped);
        //$("#df-assoc").show();
        g_snapped = this.id;
        $(this).addClass("button-assoc-selected");
    }
    else
    {
        // SWAP to OTHER ASSOC: DESELECT old, select new
        // --------------------------------------------------------
        $("#" + $("#"+g_snapped).children().data("rollover-span")).removeClass("bg-tab-summary-rollover-locked");
        $("#" + $("#"+g_snapped).children().data("rollover-span")).addClass("bg-tab-summary-rollover");
        hideAllDetails();
        $(this).addClass("button-assoc-selected");
        g_snapped = this.id;
        $("#" + $(this).data("detail-div")).show();
    }
//    $(this).addClass("assoc_active");
});


// DETAIL GRAPH BUTTONS
$(".button-bin").click(function() {
    which_id = $(this).attr('data-target');
    $("#"+which_id).attr('class', $(this).attr('data-new_class') + " pos-detail-num-graph");
});


}); // $(document).ready(...  </script>
        <style> span.icon-expand { content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAALRJREFUeNpi/P//PwM9ARMDncGohVQHLATkDYA4gEQzD0AxdgBKpTjw/P/kg/m4zMVlWQKSRgE8jkLHAkgOTcCmBlccKkDpRCD+QEJwfkDSo0DNRAMqLfbjkRcYzYeDJh8ixxk6cMAizkgtCw9gsYwBbwan0EJHLD4+gEV8NNEMrlSKr0hjpLYPH0CLp/n4iikcRdp8JDMGvnpiJNBqc0DKc8SCDUB8AWdcjDYTRy0kFQAEGAAqdjq/C2RykQAAAABJRU5ErkJggg==);}
span.icon-categorical { content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAOFJREFUeNpi/P//PwM9ARMDncGohVQHLHjkHKAYHTwA4gVQdgIQK2BRcwCKMQEolWLBCf/xgwYoxgcSsJmNy4cwVxcC8QUkcQMg7gdieyQxXGoUSA1SBqhBB6igZjSVwkE8WkqVJ1MNwVTqAMTv8aTA/VCMC7yHmoFhNiOewlsBms8YcORFBlwpEZpPHwwKH7LgKWUEoC59iBY/CVh8g02NA7bsQijRLETT5IDFQmLUjOZDlHIRH59YNQQthCXpfhzyB5Hiq5+AGURZCMtHhOrDB6TWh4yjrbZRCwe9hQABBgAyc1dqBJEdOQAAAABJRU5ErkJggg==);}
span.icon-collapse { content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJxJREFUeNpi/P//PwM9ARMDncGohVQHLATkDYA4gEQzD0AxdgBKpTjw/P/kg/m4zMVlWQKSRgE8jkLHAkgOTcCmBlccKkDpRCD+QEJwfkDSo0DPRCMwmg8HTT6E5x4i1TFSy8ID9Pah42iiGZIWfqCnhQ+gxdN8fMUUjiJtPpIZA189MRJotTlAMSlgAxBfwFkyjDYTRy0kFQAEGAD+JDS/pyABgwAAAABJRU5ErkJggg==);}

span.bg-tab-summary { position: absolute; z-index:-1000; content: url(data:image/png;base64,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);}
span.bg-tab-summary-target { position: absolute; z-index:-1000; content: url(data:image/png;base64,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);}
span.bg-tab-summary-target-full { position: absolute; z-index:-1000; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABCAAAASwCAYAAAAqijsmAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFyGlUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDggNzkuMTY0MDM2LCAyMDE5LzA4LzEzLTAxOjA2OjU3ICAgICAgICAiPiA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPiA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtbG5zOmRjPSJodHRwOi8vcHVybC5vcmcvZGMvZWxlbWVudHMvMS4xLyIgeG1sbnM6cGhvdG9zaG9wPSJodHRwOi8vbnMuYWRvYmUuY29tL3Bob3Rvc2hvcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RFdnQ9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZUV2ZW50IyIgeG1wOkNyZWF0b3JUb29sPSJBZG9iZSBQaG90b3Nob3AgMjEuMSAoV2luZG93cykiIHhtcDpDcmVhdGVEYXRlPSIyMDIwLTExLTEwVDE5OjQwOjIxLTA1OjAwIiB4bXA6TW9kaWZ5RGF0ZT0iMjAyMC0xMS0xN1QxNDozMToxMC0wNTowMCIgeG1wOk1ldGFkYXRhRGF0ZT0iMjAyMC0xMS0xN1QxNDozMToxMC0wNTowMCIgZGM6Zm9ybWF0PSJpbWFnZS9wbmciIHBob3Rvc2hvcDpDb2xvck1vZGU9IjMiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6MmZlOGM3ZDMtMzNlMC02ODRlLWE1YWMtZTkyZjAyMzA1MjYyIiB4bXBNTTpEb2N1bWVudElEPSJh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AgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByGwkQh4eHZx4AAACg2XtfJXdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMgJEAAAAEBOgAAAAAByAgQAAACQEyAAAACAnAABAAAA5AQIAAAAICdAAAAAADkBAgAAAMj9P7A6jTdMyJzmAAAAAElFTkSuQmCC);}
span.bg-tab-summary-rollover { display: none; position: absolute; z-index:-9; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABCAAAADTCAYAAABQpWLBAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAACCFJREFUeNrs3U9uW1UYxuGTqsAMsQEkdwOWO/MwrIB2B+4KmrIBkhUkrADvIGEFhJkHiFreQDNnwgyBAHMO90Z13PRPEr/Ibp5H+pRwVYnLsRSJX+/9srdcLgsAAABA0p4AAQAAAKQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxO1MgFjMZwf1y/M6Ax8bcEO/1Tmv81Odaf/PO284GvtkAQDYGTsRIBbz2ff1y8THBWzItM5RnYtd/o8QIAAA2CUPtv0G+ycfJj4qYIPaz5RXdY7rfOE4AAAg7+EO3OPzle/bY9PP6pwPR+P/HqFezGc+ReA6e3Ue1/m8zqjO13X21/7MQX+t/VyZOzIAAMjZhQAxWPn+2XA0PvOxAR+gvV/2S//9eZ2T/ufJpHRh8/LJhxYnfqzztP9zAABAwIMdu1//cwDcxUWdw9I9GbH6xEOLES1CTBwRAABk7FSAuHztAuCOLkoXIaZr19vC22PHAwAAm/fAEQD3WNv98GLtWtsLcVospwQAgI0SIID7ru2GaPsfVp+welK6VzIGjgcAADZDgAAopS23/ap0r2ZcasspX/ZfAQCAOxIgADptKeV1yylbhJg4HgAAuBsBAuC19hpGexJiunbdckoAALgjAQLgqhYh2nLKo7XrbTllCxGWUwIAwC0IEADXOyxdiFhdTjkp3XJKEQIAAG5IgAB4u2npXslYjRBtKeWrYjklAADciAAB8G5tKeWj8uZyyvYkxMTxAADAhxEgAN7vcjnl2cq1FiHaTohDxwMAAO8nQAB8mBYhntY5Wbv+belCBAAA8A4CBMDNvCjdcspVkzovi+WUAADwVgIEwM1N6zwuby6nfFkspwQAgGsJEAC305ZSPi5Xl1MOSrec8onjAQCAqwQIgNu7KN1yyvOVa+01jNPShYiBIwIAgI4AAXA3l78hY7p2fb/Oq9KFiLYz4ktHBQDAffbQEQBsRIsMP5TuN2KsLqPc76f5s86nm/oXLuYzpw4AwKqLOt8NR+OTbbw5T0AAbM5ZnUd1jsrVBZX/9POJIwIAIGhQ53gxn23lr4kXIAA2q4WHw9KFiG/q/Fzn1zq/OxoAAP4nk8V8drBtN+UVDICMFiKO+/mszl91/nYsAADc1nA0vvb6Yj5rrwDvl6uvAz+vs1WvYggQAHl/OAIAAFKGo3H7y6+zfkfYaX95sG336RUMAAAA+Dicb/PNCRAAAADwEeifhNhaAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHF7y+Vyq29wMZ8tfUwAAABwM8PReG+b7scTEAAAAECcAAEAAADE/SvAAIeUyuxDmspiAAAAAElFTkSuQmCC);}
span.bg-tab-summary-rollover-vertical { display: none; position: absolute; z-index:-9; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABCAAAAGQCAYAAAB/HhG3AAAACXBIWXMAAAsTAAALEwEAmpwYAAAF8WlUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDggNzkuMTY0MDM2LCAyMDE5LzA4LzEzLTAxOjA2OjU3ICAgICAgICAiPiA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPiA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtbG5zOmRjPSJodHRwOi8vcHVybC5vcmcvZGMvZWxlbWVudHMvMS4xLyIgeG1sbnM6cGhvdG9zaG9wPSJodHRwOi8vbnMuYWRvYmUuY29tL3Bob3Rvc2hvcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RFdnQ9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZUV2ZW50IyIgeG1wOkNyZWF0b3JUb29sPSJBZG9iZSBQaG90b3Nob3AgMjEuMSAoV2luZG93cykiIHhtcDpDcmVhdGVEYXRlPSIyMDIwLTExLTEyVDA4OjEzOjQwLTA1OjAwIiB4bXA6TW9kaWZ5RGF0ZT0iMjAyMC0xMS0xMlQwODoxOTowMi0wNTowMCIgeG1wOk1ldGFkYXRhRGF0ZT0iMjAyMC0xMS0xMlQwODoxOTowMi0wNTowMCIgZGM6Zm9ybWF0PSJpbWFnZS9wbmciIHBob3Rvc2hvcDpDb2xvck1vZGU9IjMiIHBob3Rvc2hvcDpJQ0NQcm9maWxlPSJzUkdCIElFQzYxOTY2LTIuMSIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDozMmFmYWJhMS1kNTI0LTcyNDgtYTZmNy0xYzVhMjg3YWI5OWQiIHhtcE1NOkRvY3VtZW50SUQ9ImFkb2JlOmRvY2lkOnBob3Rvc2hvcDo0YjFhOThhOC1jNTViLWM2NGYtYjJkYy05ODBmMmE4MTVmMGMiIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDoyMTZkMmQwMy00MmZkLTFmNDYtODE0Yi03OTc3YzJjZDZlMTciPiA8eG1wTU06SGlzdG9yeT4gPHJkZjpTZXE+IDxyZGY6bGkgc3RFdnQ6YWN0aW9uPSJjcmVhdGVkIiBzdEV2dDppbnN0YW5jZUlEPSJ4bXAuaWlkOjIxNmQyZDAzLTQyZmQtMWY0Ni04MTRiLTc5NzdjMmNkNmUxNyIgc3RFdnQ6d2hlbj0iMjAyMC0xMS0xMlQwODoxMzo0MC0wNTowMCIgc3RFdnQ6c29mdHdhcmVBZ2VudD0iQWRvYmUgUGhvdG9zaG9wIDIxLjEgKFdpbmRvd3MpIi8+IDxyZGY6bGkgc3RFdnQ6YWN0aW9uPSJzYXZlZCIgc3RFdnQ6aW5zdGFuY2VJRD0ieG1wLmlpZDozMmFmYWJhMS1kNTI0LTcyNDgtYTZmNy0xYzVhMjg3YWI5OWQiIHN0RXZ0OndoZW49IjIwMjAtMTEtMTJUMDg6MTk6MDItMDU6MDAiIHN0RXZ0OnNvZnR3YXJlQWdlbnQ9IkFkb2JlIFBob3Rvc2hvcCAyMS4xIChXaW5kb3dzKSIgc3RFdnQ6Y2hhbmdlZD0iLyIvPiA8L3JkZjpTZXE+IDwveG1wTU06SGlzdG9yeT4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz7hYJ5oAAARMElEQVR42u3dwY1b1xUG4J/EJNkF00AAuQFhvNPSqSB2B1IFltNA5AqsVGB1YKUCKzstgmigBqx9FpldkCAis3hDhB5L5Bs+HuPe6+8DBiM/GzBxSAg4P+85d7XdbgMAAABQaa0EAAAAQDUBBAAAAFBOAAEAAACUE0AAAAAA5QQQAAAAQDkBBAAAAFBOAAEAAACUE0AAAAAA5QQQAAAAQDkBBAAAAFBOAAEAAACUE0AAAAAA5QQQAAAAQDkBBAAAAFBOAAEAAACUE0AAAAAA5QQQAAAAQLmLXl7o2+vXT5N8meSBtw24p5skr5L8NcmL23/u3sOrR95ZAAC60cUJiLfXr79N8k2ED8BpLpN8fvv3yD+TfOvvEwAA+Hk1H0Dcnnx47K0Czuhxkh8yBRKXygEAAPV6GMH4cu/PN0meJHn18OrRTZK8vX7tXQQ+ZJXk0yS/TXKV5A9JPrvz3zy9ffYkybWSAQBAnR4CiAd7f37y8OrRS28bMMM2yd9v//wqyfPbv08eZwo2L2//3VWS75N8cfvfAQAABXq7BUNzACzxLsmzTCcjrveeX2YKIR4rEQAA1OgqgNiNXQAs9C5TCPHizvPdwlsAAODM1koA/II9SfLVnWdPk3wXyykBAOCsBBDAL93zTPsfbvaefZ5pJOOB8gAAwHkIIACSl0l+n2k0Y+cqyZvb3wAAwEICCIDJdT68nPJNLKcEAIDFBBAA/3eT6STEizvPLacEAICFBBAAP3aTaTnl13eeP80URFwqEQAA3J8AAuDDnmUKIm72nj3OtJzyUnkAAOB+BBAAH/ci00jGzd6zqyQ/xHJKAAC4FwEEwGHXST7JT5dTfh/LKQEAYDYBBMBxN5lOQrzce3aZaSfEM+UBAIDjBBAA89wk+SLJ8zvP/5QpiAAAAA4QQADcz1eZllPue5zkTSynBACAjxJAANzfiySf5qfLKd/EckoAAPggAQTAaa4zhRDXe88eZFpO+bnyAADAjwkgAE73LtNyyld7zy6TfJcpiHigRAAAMBFAACxzkymEeHHn+WdJfsgURDxJ8julAgDgl+xCCQDO4kmSv2S6EeNy7/lntz9J8p8kvz7X//Dt9WtVBwBg37skf3549eh5iy/OCQiA83mZ5JMkX+fHCyo3tz+/UiIAAAo9SPLN2+vXTV4TL4AAOK+bJM8yBRF/TPK3JP9I8i+lAQDgZ/L47fXrp629KCMYADVuknxz+/ObJP9N8l5ZAAA41cOrRx98/vb69WWmsd/9ceAvkzxv6fULIADq/VsJAACo8vDq0U2Sl7c7wr67ffygtddpBAMAAADG8KrlFyeAAAAAgAHcnoRolgACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMoJIAAAAIByAggAAACgnAACAAAAKCeAAAAAAMpddPI6t0lW3i4AAAA42j83ad1R8TY+RwAAADC7j27KhcIBAADAMLat9tJ2QAAAAADlnIAAAACAcTTbQwsgAAAAYCxN9tFGMAAAAGAcze6AcAICAAAAxuEazoXFE0IAAADA/D66OT2dgBBCAAAAQKc99IX3BgAAAIZhBGNh8Zx+AAAAgHk9dOIExFjFAwAAAD30POvOCggAAAAc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);}
span.bg-tab-summary-rollover-locked { display: inline !important; position: absolute; z-index:-9; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABCAAAADTCAYAAABQpWLBAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAACCRJREFUeNrs3U9OW1cYxuFDRNtZxQYqOTsoI0+pN9BkB84KIN1AYQXQFdQ7gG7ApUOkqnQHMO+EWdWqrXtO70UxDkn447eyw/NInyBXkeIcSyj8cu/Hxmw2KwAAAABJzxwBAAAAkCZAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQJ0AAAAAAcQIEAAAAECdAAAAAAHECBAAAABAnQAAAAABxAgQAAAAQt7kuL/RqNNyrH3brDLxtwH2/hNQ5rfNTnUn/67W3NT3zzgIAsDY2ZrPZ6n/nMBp+Xz+MvV3AkkzqHNS5XOe/hAABAMA6WflHMPo7H8beKmCJ2teUizqH7ft4xwEAAHnr8AjG7tzn7bbpV3VOt6Zn/91CfTUaeheB22zU2a7zeZ0v63xdZ2fh9+z119rXlV8dGQAA5KxDgBjMff5qa3p24m0D7qA9X/ZL//lpnaP+68m4dGHz+s6HFid+rPOy/30AAEDAuv0UDN8cAI9xWWe/dHdGzN/x0GJEixBjRwQAABlrFSCuH7sAeKTL0kWIycL1tvD20PEAAMDyPXMEwBPWdj+8XrjW9kIcF8spAQBgqQQI4KlruyHa/of5O6xelO6RjIHjAQCA5RAgAEppy22/Kt2jGdfacsrz/iMAAPBIAgRApy2lvG05ZYsQY8cDAACPI0AAvNEew2h3QkwWrltOCQAAjyRAANzUIkRbTnmwcL0tp2whwnJKAAB4AAEC4Hb7pQsR88spx6VbTilCAADAPQkQAO82Kd0jGfMRoi2lvCiWUwIAwL0IEADv15ZSPi9vL6dsd0KMHQ8AANyNAAHwYdfLKU/mrrUI0XZC7DseAAD4MAEC4G5ahHhZ52jh+relCxEAAMB7CBAA9/O6dMsp543rnBfLKQEA4J0ECID7m9TZLm8vpzwvllMCAMCtBAiAh2lLKbfLzeWUg9Itp3zheAAA4CYBAuDhLku3nPJ07lp7DOO4dCFi4IgAAKAjQAA8zvVPyJgsXN+pc1G6ENF2RnzhqAAAeMo2HQHAUrTI8EPpfiLG/DLKnX6aP+t8uqw/8Go0dOoAAMy7rPPd1vTsaBVfnDsgAJbnpM7zOgfl5oLKf/r5xBEBABA0qHN4NRqu5I+JFyAAlquFh/3ShYhv6vxc57c6vzsaAAD+J+Or0XBv1V6URzAAMlqIOOznszp/1fnbsQAA8FBb07Pb/+E5GrZHgHfKzceBd+us1KMYAgRA3h+OAACAlK3pWfvPr5N+R9hxf3mwaq/TIxgAAADwcThd5RcnQAAAAMBHoL8TYmUJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxAkQAAAAQJwAAQAAAMQJEAAAAECcAAEAAADECRAAAABAnAABAAAAxG2u04u9Gg1n3jIAAACeovo98Vq/fndAAAAAAHECBAAAABD3rwADAFbxkg002cszAAAAAElFTkSuQmCC);}
span.bg-tab-detail-med { position: absolute; z-index:-10; width: 655px; content: url(data:image/png;base64,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);}
/* used in assoc */
span.bg-tab-detail-wide { position: absolute; z-index:-10; width: 879px; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA5gAAAF8CAYAAACqghQAAAAACXBIWXMAAAsTAAALEwEAmpwYAAAF8WlUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDggNzkuMTY0MDM2LCAyMDE5LzA4LzEzLTAxOjA2OjU3ICAgICAgICAiPiA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPiA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtbG5zOmRjPSJodHRwOi8vcHVybC5vcmcvZGMvZWxlbWVudHMvMS4xLyIgeG1sbnM6cGhvdG9zaG9wPSJodHRwOi8vbnMuYWRvYmUuY29tL3Bob3Rvc2hvcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RFdnQ9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZUV2ZW50IyIgeG1wOkNyZWF0b3JUb29sPSJBZG9iZSBQaG90b3Nob3AgMjEuMSAoV2luZG93cykiIHhtcDpDcmVhdGVEYXRlPSIyMDIwLTA0LTEyVDA1OjQ0OjA0LTA0OjAwIiB4bXA6TW9kaWZ5RGF0ZT0iMjAyMC0wNC0yNFQwODoyOTowNC0wNDowMCIgeG1wOk1ldGFkYXRhRGF0ZT0iMjAyMC0wNC0yNFQwODoyOTowNC0wNDowMCIgZGM6Zm9ybWF0PSJpbWFnZS9wbmciIHBob3Rvc2hvcDpDb2xvck1vZGU9IjMiIHBob3Rvc2hvcDpJQ0NQcm9maWxlPSJzUkdCIElFQzYxOTY2LTIuMSIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDo5Yzk4ZTJlMi05NjRjLWNmNDEtOGU4Yy0yMjMyYzc1OTdjN2QiIHhtcE1NOkRvY3VtZW50SUQ9ImFkb2JlOmRvY2lkOnBob3Rvc2hvcDpjMjdhOGM2Ni0zZDYzLTE2NDAtOGFiMS1jYTVkOTRlMTc1OWQiIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDowYmUzNzNjOS1lNDhlLWRhNGMtOWY1ZC0zOTdlNTg1M2RkZDYiPiA8eG1wTU06SGlzdG9yeT4gPHJkZjpTZXE+IDxyZGY6bGkgc3RFdnQ6YWN0aW9uPSJjcmVhdGVkIiBzdEV2dDppbnN0YW5jZUlEPSJ4bXAuaWlkOjBiZTM3M2M5LWU0OGUtZGE0Yy05ZjVkLTM5N2U1ODUzZGRkNiIgc3RFdnQ6d2hlbj0iMjAyMC0wNC0xMlQwNTo0NDowNC0wNDowMCIgc3RFdnQ6c29mdHdhcmVBZ2VudD0iQWRvYmUgUGhvdG9zaG9wIDIxLjEgKFdpbmRvd3MpIi8+IDxyZGY6bGkgc3RFdnQ6YWN0aW9uPSJzYXZlZCIgc3RFdnQ6aW5zdGFuY2VJRD0ieG1wLmlpZDo5Yzk4ZTJlMi05NjRjLWNmNDEtOGU4Yy0yMjMyYzc1OTdjN2QiIHN0RXZ0OndoZW49IjIwMjAtMDQtMjRUMDg6Mjk6MDQtMDQ6MDAiIHN0RXZ0OnNvZnR3YXJlQWdlbnQ9IkFkb2JlIFBob3Rvc2hvcCAyMS4xIChXaW5kb3dzKSIgc3RFdnQ6Y2hhbmdlZD0iLyIvPiA8L3JkZjpTZXE+IDwveG1wTU06SGlzdG9yeT4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz54wJMsAAAWwElEQVR42u3dX4wc90HA8Zm7vcvZvkvikESJa5KQSEChkASa5n8TqJCMkXBfELwVAUJIeaoixAP0ASkSEgIJCZAAEf480Qce4iJcvwCVaJqm+e+kceIqrV2QIE1UEt85cezzDrvpbjwez+zd3s5v9zc7n4802b2zfTeZ3Z3b7/1mftPJsiwBAACASXUm/QJHjxze6q+kNjNj8lsPGuHAwUOh959Bvz8AQHSBuYOgHDc4xUb7+KWESAcAoOWBmY75sdgQGoR7rFPPAwAAmhiY6Rb3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);}

span.bg-detail-column { position: relative; z-index:-10; content: url(data:image/png;base64,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);}
span.bg-extra-column { position: absolute; z-index:-10; width: 295px; height: 275px; content: url(data:image/png;base64,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);}

div.ic-cat { z-index: 1; position: absolute; content: url(data:image/png;base64,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);}
div.ic-cat-light { z-index: 1; position: absolute; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAP1JREFUeNpi/P//PwM9ARMDncGohVQHLLgkNqyc6wCkHLBIPQgIT14AVZMApBSwqDkAVHMAm7mM2FIp1KD5eBzaCKXr8ahJhDmMGB/CXF0IxBeQxA2AuB+I7ZHEcKlRIClIoeACctAAfU6umtFUCgfx0NQKA/JkqiFoIShO8oE4gQhHY1PzAWoGcdkCGvkKeCx8gJaa0cECYEJ6QEo+BAXReiAWwBMCDDgKBpgPA7FlflxB6gC1DJRxH6LFD7qvcalxwBashBLNQrQ85oDFQmLUjOZDRLmIVlQZkKmGoIWwJN2PQ/4gUuLqJ2AG0fmQfvXhaJtm1MJBZSFAgAEArrBnthzR+WkAAAAASUVORK5CYII=);}
div.ic-numeric { z-index: 1; position: absolute; content: url(data:image/png;base64,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);}
div.ic-numeric-light { z-index: 1; position: absolute; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAASRJREFUeNrsVtENgjAQReMAjKAb6ATiBNYvP4U4ACOgG+gABvj0jw3UCWQER2ADfI2PxFQDIoUQpcnlJU3v3r27XtNemqZGk6tvNLz+lDA6HoawcZMKfdj1J0o6KOuAUlsAFyZgN1golutNLQpJdiJZDDNhHvb9ukqaBXagagIcUaXNZPQRIqANGMLOIAvkHjABbHnE1a1wTtw/b5JcqhRynLQQIpDJviUgiN4dIVq6FAolsLpC4qoyIdV5SmBDKWvMslrs9XdzCOcNs5a9CRD4nHPc4cj48JsCLzIEL9bHCj2S7eDo5Nb8kcwiGxOOkCj70szkgKtZ5pDKHkdPMxmXIiwo4Vd+7Xq8UZqqH54Jb3Ah4UWToJfe97pfW0fYesK7AAMAvAljVNSArLoAAAAASUVORK5CYII=);}
div.ic-text { z-index: 1; position: absolute; content: url(data:image/png;base64,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);}

span.top-header {  position: absolute; z-index:-1000; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAlgAAACgCAYAAADQOBKBAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAA5RJREFUeNrs3MFNAkEUgGEGKYASrEDxIoletAPtwBaohBbsQDvQiyRwUajAEraDdV7cg1fji+6Y70te5DSZDJc/w7ql7/sJAAB5po4AAEBgAQAILAAAgQUAgMACABBYAAACCwAAgQUA8AdmWQuVUib77cu8flzXuXO0AEBD7uusTpeXXcZL2EvWm9wPu03E1VOd+Ht7cn7xFtEFADBW0UG1YRb140Odrs51bZjup+tm/kQYN1fHdc7EFQDQguiV6Jbol6Fj1hnrZgbWzeTz5qoTVwBAY5EVt1a3Q8+MKrBic8/iCgBoNLKes9abZW8w65kuAIBWeU0DAIDAAgAQWAAAAgsAAIEFACCwAAAEFgAAAgsAQGABAAgsAAAEFgCAwAIAEFgAAAILAACBBQAgsAAABBYAAAILAEBgAQAILAAABBYAgMACABBYAAAILAAAgQUAILAAAAQWAAACCwBAYAEACCwAAAQWAMA/CqwjxwkANC6lZwQWAMCIA6v4TgAAgeUGCwDgq5QLI4EFAJDcM5mB5T8SAYDWTUezyMAzWABA60b3EyEAAAILAEBgAQAILAAAgQUAgMACABBYAAACCwAAgQUAILAAAAQWAAACCwBAYAEACCwAAIEFAIDAAgAQWAAAAgsAAIEFACCwAAAEFgAAAgsAQGABAAgsAAAEFgCAwAIAEFgAAAILAACBBQAgsAAABBYAAAILAEBgAQAILAAABBYAgMACABBYAAAILAAAgQUAILAAAAQWAAACCwBAYAEACCwAAAQWAIDAAgAQWAAACCwAAIEFACCwAAAQWAAAAgsAQGABAAgsAAAEFgCAwAIAEFgAAAgsAACBBQAgsAAAEFgAAAILAEBgAQAILEcAACCwAAAEFgCAwAIAQGABAAgsAACBBQCAwAIAEFgAAAILAACBBQAgsAAABBYAgMACAEBgAQAILAAAgQUAgMACABBYAAACCwAAgQUAILAAAAQWAAACCwBAYAEACCwAAIEFAIDAAgAQWAAAAgsAgG+aZS9YSnGqAEBz+r5PWyvzBqs77DZXmZsDAPiNsIqJjomeGVtgPdZ5qJubiywAoCXRL9ExQ8+MKrBWdd7rvNZNLkQWADB2w83VIvpl6JhVxrolK4Ti2av99iXqb13nzlcGADTkPuLqdHnZZbRRcdMEAJDLaxoAAAQWAIDAAgAQWAAACCwAAIEFACCwAAAQWAAAf+FDgAEA8Z1pNK1F390AAAAASUVORK5CYII=);}

div.tab-summary-rollover { content: url(data:image/png;base64,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);}
div.tab-summary-target { content: url(data:image/png;base64,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);}

div.im-logo { content: url(data:image/png;base64,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);}

div.ic-missing-green { position: absolute; top: 2px; z-index: -1; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAANCAYAAAAjf9cfAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAM+aVRYdFhNTDpjb20uYWRvYmUueG1wAAAAAAA8P3hwYWNrZXQgYmVnaW49Iu+7vyIgaWQ9Ilc1TTBNcENlaGlIenJlU3pOVGN6a2M5ZCI/Pg0KPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDggNzkuMTY0MDM2LCAyMDE5LzA4LzEzLTAxOjA2OjU3ICAgICAgICAiPg0KICA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPg0KICAgIDxyZGY6RGVzY3JpcHRpb24gcmRmOmFib3V0PSIiIHhtbG5zOnhtcD0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bXA6Q3JlYXRvclRvb2w9IkFkb2JlIFBob3Rvc2hvcCAyMS4xIChXaW5kb3dzKSIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDo4MTJBRjA2MjBFRTkxMUVCOTZFRjlFQjhDNkQ5OEJCNCIgeG1wTU06RG9jdW1lbnRJRD0ieG1wLmRpZDo4MTJBRjA2MzBFRTkxMUVCOTZFRjlFQjhDNkQ5OEJCNCI+DQogICAgICA8eG1wTU06RGVyaXZlZEZyb20gc3RSZWY6aW5zdGFuY2VJRD0ieG1wLmlpZDo4MTJBRjA2MDBFRTkxMUVCOTZFRjlFQjhDNkQ5OEJCNCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDo4MTJBRjA2MTBFRTkxMUVCOTZFRjlFQjhDNkQ5OEJCNCIgLz4NCiAgICA8L3JkZjpEZXNjcmlwdGlvbj4NCiAgPC9yZGY6UkRGPg0KPC94OnhtcG1ldGE+DQo8P3hwYWNrZXQgZW5kPSJyIj8+OjfJSQAAAIxJREFUSEvtlLEJg0AUQE3qELJEyAoOIJlJsJdM4wDBASzS2AlZIsT0+t4AWt79Ig/eIdf8Byf/8FrGAq74wArPXiTiiz3W+DbmxseAF8zFB8sjR4s5Q8T5rTE+TQTuxqT8R/Y4GROGf8wW4WJcPBH4GeMGjMDTmAbdgDlxfmPMhCV2OGNKnOdc5hfTCl5aGNzdDpDTAAAAAElFTkSuQmCC);}
div.ic-missing-yellow { position: absolute; top: 2px; z-index: -1; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAANCAYAAAAjf9cfAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAM+aVRYdFhNTDpjb20uYWRvYmUueG1wAAAAAAA8P3hwYWNrZXQgYmVnaW49Iu+7vyIgaWQ9Ilc1TTBNcENlaGlIenJlU3pOVGN6a2M5ZCI/Pg0KPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDggNzkuMTY0MDM2LCAyMDE5LzA4LzEzLTAxOjA2OjU3ICAgICAgICAiPg0KICA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPg0KICAgIDxyZGY6RGVzY3JpcHRpb24gcmRmOmFib3V0PSIiIHhtbG5zOnhtcD0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bXA6Q3JlYXRvclRvb2w9IkFkb2JlIFBob3Rvc2hvcCAyMS4xIChXaW5kb3dzKSIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDo5M0ZFRDVDMTBFRTkxMUVCODk1OEU0QjM1RDdCNDUzRCIgeG1wTU06RG9jdW1lbnRJRD0ieG1wLmRpZDo5M0ZFRDVDMjBFRTkxMUVCODk1OEU0QjM1RDdCNDUzRCI+DQogICAgICA8eG1wTU06RGVyaXZlZEZyb20gc3RSZWY6aW5zdGFuY2VJRD0ieG1wLmlpZDo5M0ZFRDVCRjBFRTkxMUVCODk1OEU0QjM1RDdCNDUzRCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDo5M0ZFRDVDMDBFRTkxMUVCODk1OEU0QjM1RDdCNDUzRCIgLz4NCiAgICA8L3JkZjpEZXNjcmlwdGlvbj4NCiAgPC9yZGY6UkRGPg0KPC94OnhtcG1ldGE+DQo8P3hwYWNrZXQgZW5kPSJyIj8+kNAGTgAAAI1JREFUSEvtlMEJg0AQAE3eIaSJkBYsQFKT4F/Shg2kALGAlCDYREh85CM4U4A+7/aRgTnkPjtwsofl1xVwxQdWePYiER8csMbJmBsfL7xgLt5YHjlazBkizm+N8WkicDcm5T+yx8mYMPxjtggX4+KJwGyMGzACvTENugFz4vzGmBFLfOIXU+I85zK/GFcMlhjQAEQbWgAAAABJRU5ErkJggg==);}
div.ic-missing-orange { position: absolute; top: 2px; z-index: -1; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAANCAYAAAAjf9cfAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAM+aVRYdFhNTDpjb20uYWRvYmUueG1wAAAAAAA8P3hwYWNrZXQgYmVnaW49Iu+7vyIgaWQ9Ilc1TTBNcENlaGlIenJlU3pOVGN6a2M5ZCI/Pg0KPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDggNzkuMTY0MDM2LCAyMDE5LzA4LzEzLTAxOjA2OjU3ICAgICAgICAiPg0KICA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPg0KICAgIDxyZGY6RGVzY3JpcHRpb24gcmRmOmFib3V0PSIiIHhtbG5zOnhtcD0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wLyIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bXA6Q3JlYXRvclRvb2w9IkFkb2JlIFBob3Rvc2hvcCAyMS4xIChXaW5kb3dzKSIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDpBMzAyOEVCNzBFRTkxMUVCQkJCQ0MzQzAxODVGOEJCQSIgeG1wTU06RG9jdW1lbnRJRD0ieG1wLmRpZDpBMzAyOEVCODBFRTkxMUVCQkJCQ0MzQzAxODVGOEJCQSI+DQogICAgICA8eG1wTU06RGVyaXZlZEZyb20gc3RSZWY6aW5zdGFuY2VJRD0ieG1wLmlpZDpBMzAyOEVCNTBFRTkxMUVCQkJCQ0MzQzAxODVGOEJCQSIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDpBMzAyOEVCNjBFRTkxMUVCQkJCQ0MzQzAxODVGOEJCQSIgLz4NCiAgICA8L3JkZjpEZXNjcmlwdGlvbj4NCiAgPC9yZGY6UkRGPg0KPC94OnhtcG1ldGE+DQo8P3hwYWNrZXQgZW5kPSJyIj8+YUIbjgAAAIxJREFUSEvtlMEJg0AQAE3eIdiEpAULkBSQagL+xV4CFiApwBKENBFi/jpTQHze7SMDc8h9duBkD+vjVkCFPTZ49iIRH3ziHV/GXPiYsMRcvLE+cnSYM0Sc3xnj00TgakzKf2SPkzFh+Mf8IlyMiycCX2PcgBEYjWnRDZgT57fGzFjjgAumxHnOZX4xb8aXF5wsqUu9AAAAAElFTkSuQmCC);}
div.ic-missing-red { position: absolute; top: 2px; z-index: -1; content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAANCAYAAAAjf9cfAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyNpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNi1jMTQ4IDc5LjE2NDAzNiwgMjAxOS8wOC8xMy0wMTowNjo1NyAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIxLjEgKFdpbmRvd3MpIiB4bXBNTTpJbnN0YW5jZUlEPSJ4bXAuaWlkOkJEODI2MzE0MEVFOTExRUJBMDkyRkY5QkEwNEU4NThBIiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOkJEODI2MzE1MEVFOTExRUJBMDkyRkY5QkEwNEU4NThBIj4gPHhtcE1NOkRlcml2ZWRGcm9tIHN0UmVmOmluc3RhbmNlSUQ9InhtcC5paWQ6QkQ4MjYzMTIwRUU5MTFFQkEwOTJGRjlCQTA0RTg1OEEiIHN0UmVmOmRvY3VtZW50SUQ9InhtcC5kaWQ6QkQ4MjYzMTMwRUU5MTFFQkEwOTJGRjlCQTA0RTg1OEEiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz4XpOIDAAAAhUlEQVR42mL8L8DJAASqQNwBxC5AzMdAP/AJiPcAcQUQ32YEOkYdyDgBxAIMAwc+ALEFyDFrgYwghoEH60CO+UjnqMEFvjANEoeAAA8TwyACo44ZMo75NEjcAs5NewaJY3aByhkNIOP4ICiBLUEhcwNUFINKQCD+TGdHfIbaC7L/BkCAAQAYcRpVGFqHAwAAAABJRU5ErkJggg==);} </style>
        <style> @font-face
{
    font-family: RobotoBoldCond; font-style: normal; font-weight: normal;
    src: url(data:font/truetype;charset=utf-8;base64,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/73/6f+u/70AAP+l/68AAAAAAAAAEgASAAD/0gAAAAAAAAAAAAAAAAAAAAAAAAAA/8r+d/+7AAAAAAAA/zkAAP/pAAAAAAAAAAIANwAGAAYAGQALAAsAGQAQABAAIQASABIAIQAlACUAAgAmACYAHAAnACcAEwAoACgAAQApACkABQAuAC4ACgAvAC8ACwAwADAAGAAzADMAAQA0ADQAFgA4ADgADgA5ADkACgA6ADoAHQA7ADsAGwA8ADwAEgA9AD0ADAA+AD4AEQBFAEUABgBGAEYABwBHAEcAFwBJAEkACABMAEwABABRAFIABABTAFMAAwBUAFQABwBWAFYAFQBaAFoACQBcAFwAFABdAF0ACQBeAF4AEACDAIgAAgCKAIoAEwCLAI4ABQCTAJMAAQCVAJkAAQCcAJ8ACgCgAKAADACjAKgABgCqAKoAFwCrAK4ACAC0ALQABAC1ALkAAwDAAMAACQDBAMEABwDCAMIACQDFAMUADADYANkAGQDaANoAIQDbANwAGQDdAN0AIQDfAN8AIQACADcABgAGABQACwALABQAEAAQABoAEQARAB8AEgASABoAJQAlAAYAJwAnAAIAKwArAAIALgAuACMAMwAzAAIANQA1AAIANwA3ABAAOAA4AAsAOQA5AAoAOgA6AB0AOwA7ABYAPAA8ABEAPQA9AAwAPgA+ABMARQBFAAcARwBJAAEASwBLAAEAUQBSAAMAUwBTAAQAVABUAAMAVQBVAAEAVwBXAA4AWQBZAAUAWgBaAAkAXABcABUAXQBdAAkAXgBeAA8AcABwAB8AgwCIAAYAigCKAAIAlQCZAAIAmwCbAAIAnACfAAoAoACgAAwAowCoAAcAqgCuAAEAtAC0AAMAtQC5AAQAvAC/AAUAwADAAAkAwgDCAAkAwwDDAAIAxADEAAEAxQDFAAwA1gDXAB8A2ADZABQA2gDaABoA2wDcABQA3QDdABoA3wDfABoAAgAYAAYABgAAAAsACwABABAAEAACABIAEgADACUAKQAEACwANAAJADgAPgASAEUARwAZAEkASQAcAEwATAAdAFEAVAAeAFYAVgAiAFoAWgAjAFwAXgAkAIMAiAAnAIoAmQAtAJwAoAA9AKMAqABCAKoArgBIALQAuQBNAMAAwgBTAMUAxQBWANgA3QBXAN8A3wBdAAEAAAAKAJ4A4AAE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AGgAcgBpAHMAdABpAGEAbgAgAFIAbwBiAGUAcgB0AHMAbwBuAEwAaQBjAGUAbgBzAGUAZAAgAHUAbgBkAGUAcgAgAHQAaABlACAAQQBwAGEAYwBoAGUAIABMAGkAYwBlAG4AcwBlACwAIABWAGUAcgBzAGkAbwBuACAAMgAuADAAaAB0AHQAcAA6AC8ALwB3AHcAdwAuAGEAcABhAGMAaABlAC4AbwByAGcALwBsAGkAYwBlAG4AcwBlAHMALwBMAEkAQwBFAE4AUwBFAC0AMgAuADAAVwBlAGIAZgBvAG4AdAAgADEALgAwAFQAaAB1ACAAQQBwAHIAIAAgADIAIAAxADAAOgA1ADkAOgA1ADEAIAAyADAAMgAwAGQAZQBmAGEAdQBsAHQAcABlAHIAcwBlAHUAcwBGAG8AbgB0ACAAUwBxAHUAaQByAHIAZQBsAAIAAAAAAAD9dgBkAAAAAAAAAAAAAAAAAAAAAAAAAAAA6wAAAQIBAwEEAAMABAAFAAYABwAIAAkACgALAAwADQAOAA8AEAARABIAEwAUABUAFgAXABgAGQAaABsAHAAdAB4AHwAgACEAIgAjACQAJQAmACcAKAApACoAKwAsAC0ALgAvADAAMQAyADMANAA1ADYANwA4ADkAOgA7ADwAPQA+AD8AQABBAEIAQwBEAEUARgBHAEgASQBKAEsATABNAE4ATwBQAFEAUgBTAFQAVQBWAFcAWABZAFoAWwBcAF0AXgBfAGAAYQEFAKMAhACFAL0AlgDoAIYAjgCLAJ0AqQCkAQYAigDaAIMAkwEHAQgAjQCXAIgAwwDeAQkAngCqAPUA9AD2AKIArQDJAMcArgBiAGMAkABkAMsAZQDIAMoAzwDMAM0AzgDpAGYA0wDQANEArwBnAPAAkQDWANQA1QBoAOsA7QCJAGoAaQBrAG0AbABuAKAAbwBxAHAAcgBzAHUAdAB2AHcA6gB4AHoAeQB7AH0AfAC4AKEAfwB+AIAAgQDsAO4AugCwALEAuwDYANkBCgELAQwBDQEOAQ8BEAERARIBEwEUARUBFgEXALIAswC2ALcAxAC0ALUAxQCHAKsBGAC+AL8BGQEaAIwBGwEcAR0BHgEfBmdseXBoMQd1bmkwMDBEB3VuaTAwMDIHdW5pMDBBMAd1bmkwMEFEB3VuaTAwQjIHdW5pMDBCMwd1bmkwMEI5B3VuaTIwMDAHdW5pMjAwMQd1bmkyMDAyB3VuaTIwMDMHdW5pMjAwNAd1bmkyMDA1B3VuaTIwMDYHdW5pMjAwNwd1bmkyMDA4B3VuaTIwMDkHdW5pMjAwQQd1bmkyMDEwB3VuaTIwMTEKZmlndXJlZGFzaAd1bmkyMDJGB3VuaTIwNUYERXVybwd1bmkyNUZDB3VuaUZCMDEHdW5pRkIwMgd1bmlGQjAzB3VuaUZCMDQAuAH/hbABjQBLsAhQWLEBAY5ZsUYGK1ghsBBZS7AUUlghsIBZHbAGK1xYALADIEWwAytEsAsgRbID/wIrsAMrRLAKIEWyC4oCK7ADK0SwCSBFsgo/AiuwAytEsAggRbIJLgIrsAMrRLAHIEWyCCYCK7ADK0SwBiBFsgeyAiuwAytEsAUgRbIGHgIrsAMrRLAEIEWyBRUCK7ADK0SwDCBFsgMdAiuwAytEsA0gRbIMHAIrsAMrRAGwDiBFsAMrRLASIEWyDmUCK7EDRnYrRLARIEWyElECK7EDRnYrRLAQIEWyETwCK7EDRnYrRLAPIEWyEC4CK7EDRnYrRLATIEW6AA5//wACK7EDRnYrRLAUIEW6ABMBDAACK7EDRnYrRLAVIEWyFJwCK7EDRnYrRLAWIEWyFVACK7EDRnYrRFmwFCs=) format('truetype');
}
@font-face
{
    font-family: RobotoMed; font-style: normal; font-weight: normal;
    src: url(data:font/truetype;charset=utf-8;base64,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/73/6f+u/70AAP+l/68AAAAAAAAAEgASAAD/0gAAAAAAAAAAAAAAAAAAAAAAAAAA/8r+d/+7AAAAAAAA/zkAAP/pAAAAAAAAAAIANwAGAAYAGQALAAsAGQAQABAAIQASABIAIQAlACUAAgAmACYAHAAnACcAEwAoACgAAQApACkABQAuAC4ACgAvAC8ACwAwADAAGAAzADMAAQA0ADQAFgA4ADgADgA5ADkACgA6ADoAHQA7ADsAGwA8ADwAEgA9AD0ADAA+AD4AEQBFAEUABgBGAEYABwBHAEcAFwBJAEkACABMAEwABABRAFIABABTAFMAAwBUAFQABwBWAFYAFQBaAFoACQBcAFwAFABdAF0ACQBeAF4AEACDAIgAAgCKAIoAEwCLAI4ABQCTAJMAAQCVAJkAAQCcAJ8ACgCgAKAADACjAKgABgCqAKoAFwCrAK4ACAC0ALQABAC1ALkAAwDAAMAACQDBAMEABwDCAMIACQDFAMUADADYANkAGQDaANoAIQDbANwAGQDdAN0AIQDfAN8AIQACADcABgAGABQACwALABQAEAAQABoAEQARAB8AEgASABoAJQAlAAYAJwAnAAIAKwArAAIALgAuACMAMwAzAAIANQA1AAIANwA3ABAAOAA4AAsAOQA5AAoAOgA6AB0AOwA7ABYAPAA8ABEAPQA9AAwAPgA+ABMARQBFAAcARwBJAAEASwBLAAEAUQBSAAMAUwBTAAQAVABUAAMAVQBVAAEAVwBXAA4AWQBZAAUAWgBaAAkAXABcABUAXQBdAAkAXgBeAA8AcABwAB8AgwCIAAYAigCKAAIAlQCZAAIAmwCbAAIAnACfAAoAoACgAAwAowCoAAcAqgCuAAEAtAC0AAMAtQC5AAQAvAC/AAUAwADAAAkAwgDCAAkAwwDDAAIAxADEAAEAxQDFAAwA1gDXAB8A2ADZABQA2gDaABoA2wDcABQA3QDdABoA3wDfABoAAgAYAAYABgAAAAsACwABABAAEAACABIAEgADACUAKQAEACwANAAJADgAPgASAEUARwAZAEkASQAcAEwATAAdAFEAVAAeAFYAVgAiAFoAWgAjAFwAXgAkAIMAiAAnAIoAmQAtAJwAoAA9AKMAqABCAKoArgBIALQAuQBNAMAAwgBTAMUAxQBWANgA3QBXAN8A3wBdAAEAAAAKAJ4A4AAE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6bIKBAors0AKCAkrtBUWGwQNK7EVB+kBsB8vsADWsQ4M6bAOELETASuwCDKxGAzpsAcyshMYCiuzQBMVCSuxIAErsRMOERKyCgQbOTk5ALEVERESsBg5MDETNRAAITIEFyMCISIGBxUUEjMyNxEhNSERBgQjIiQCagE8ARvzAR4d+Cr++aqxA8exwlL+1AIoT/7osrf+5pkClXIBSgFz8OIBB/XtcOz++1gBHcD90mdqpgE1AAEAlAAABRgFsAALAD8AsgAAACuwBzOyAQIAK7AFM7QDCgABDSuxAwPpAbAML7AA1rELDOmwAjKwCxCxCAErsAQysQcM6bENASsAMDEzETMRIREzESMRIRGU/QKL/Pz9dQWw/aICXvpQAof9eQAAAAABAKMAAAGfBbAAAwAhALIAAAArsgECACsBsAQvsADWsQMM6bEDDOmxBQErADAxMxEzEaP8BbD6UAAAAAABAC3/7APkBbAADwA/ALINAAArsQQD6bIEDQors0AEAAkrsggCACsBsBAvsADWsQEM6bABELEHASuxCgzpsREBK7EHARESsA05ADAxEzMUFjMyNjURMxEUBCMiJi38c21mefz++9bk+AGfdHWHdwP8/APR9uYAAAABAJQAAAUYBbAADAAwALIAAAArsAgzsgECACuwBTMBsA0vsADWsQwM6bACMrEOASsAsQEAERKxAwo5OTAxMxEzETcBIQkBIQEHEZT9jAGqATL94wI8/tT+SqUFsP1VrQH+/Xv81QJ1r/46AAABAJQAAAQmBbAABQAsALIAAAArsQMD6bIBAgArAbAGL7AA1rEDDOmyAwAKK7NAAwUJK7EHASsAMDEzETMRIRWU/QKVBbD7GsoAAAAAAQCUAAAGagWwAA4AVwCyAAAAK7EGCjMzsgECACuwBDMBsA8vsADWsQ4M6bEMD+mwDhCxBwErsQYM6bAGELEJD+mwCS+xEAErsQcOERKzAgQKCyQXOQCxAQARErIDCQw5OTkwMTMRIQkBIREjERMBIwETEZQBSAGkAaMBR/wZ/lK1/lMZBbD7pARc+lAB4AKC+54EYf1//iAAAAAAAQCUAAAFFwWwAAkARgCyAAAAK7AGM7IBAgArsAQzAbAKL7AA1rEJDOmwCRCxAwErsQYM6bELASuxCQARErACObADEbAHOQCxAQARErEDCDk5MDEzETMBETMRIwERlP0Ci/v9/XcFsPvzBA36UAQJ+/cAAAACAGb/7AUeBcQAEAAeADwAsg0AACuxFAnpsgUCACuxGwnpAbAfL7AA1rERDOmwERCxFwErsQkM6bEgASuxFxERErIFBA05OTkAMDETNTQSJCAEEhcVFAIEIyIkAjcUEjMyEj0BNAIjIgIHZpcBEwFkAROWAZT+7bOx/uuX/LumqLW3qKS5AgKqUtUBRq2r/r/VUdb+va2tAUDZ8P76AQD2TPIBAv7/6wACAJQAAATUBbAACgATAEIAsgAAACuyAQIAK7ETA+m0CQsAAQ0rsQkD6QGwFC+wANaxCgzpsAsysAoQsQ8BK7EFDOmxFQErALETCxESsAU5MDEzESEyBBUUBCMhGQEhMjY1NCYnIZQCLfQBH/7n/f7TATCHjpB+/skFsP7R1u794wLof3h2jQIAAgBg/wQFGgXEABUAIwBPALISAAArsRkJ6bIFAgArsSAJ6QGwJC+wANaxFgzpsBYQsRwBK7EKDOmwDjKxJQErsRwWERKyEBIFOTk5sAoRsQ0POTkAsRkSERKwDTkwMRM1NBIkMzIEEhcVFAIHFwclBiMiJAI3FBIzMhI9ATQmIyICB2CXAROxtAETlgGDdvqk/so9RrD+65f8uaeptbioo7kCAqpS1QFGrav+v9VRz/7RWcOU9Q2tAUDZ7P72AQD2TPb+/v/qAAACAJQAAATeBbAADgAXAGEAsgAAACuwCjOyAQIAK7EXA+m0DQ8AAQ0rsQ0D6QGwGC+wANaxDgzpsA8ysA4QsRMBK7EFDOmxGQErsRMOERKxDAg5ObAFEbALOQCxDQARErAJObAPEbAIObAXErAFOTAxMxEhMgQVFAYHARUhASEZASEyNjU0JichlAIA/AESjX4BR/7x/tz+5gEEgJCFhP71BbDi1pLFNf2hDQIx/c8C/IFwdYACAAAAAQBK/+wEigXEACcAbQCyJAAAK7EECOmyBCQKK7NABAAJK7IQAgArsRgD6bIYEAors0AYFAkrAbAoL7AN1rEbDOmwACDWEbEBDOmwGxCxBwErsBUysSEM6bAUMrEpASuxBxsRErQEChAeJCQXOQCxGAQRErENITk5MDETMxQWMzI2NTQmJCcmNTQkMzIeARUjNCYjIgYVFBYEHgEVFAQjIiQmSv2kmYSFh/6gaMcBH+WY7oj8j4V8iZQBVM5g/unvnv73kwG4fIhrWGBoakF9ybDkcM9+coFqX1BrZYGncLbXdc4AAQAtAAAEsAWwAAcAOgCyBgAAK7IBAgArsQAD6bADMgGwCC+wBtaxBQzpsgUGCiuzQAUDCSuyBgUKK7NABgAJK7EJASsAMDETNSEVIREjES0Eg/46+wTkzMz7HATkAAAAAQB9/+wEvQWwABAANwCyDgAAK7EGA+myAQIAK7AJMwGwES+wANaxAwzpsAMQsQgBK7ELDOmxEgErsQgDERKwDjkAMDETETMRFBYzIBkBMxEUACMiAH38lJABJPz+1/f6/toB5APM/DKSmgE0A8b8M+j+8QELAAAAAQASAAAFHQWwAAYAPQCyBgAAK7IAAgArsAMzAbAHL7AA1rEBFemwARCxAwErsQQV6bEIASuxAwERErEFBjk5ALEABhESsAI5MDETIQkBIQEjEgEVAW4BcgEW/fT1BbD7jQRz+lAAAAABADAAAAblBbAADACRALIMAAArsQkLMzOyAAIAK7IDBAYzMzMBsA0vsADWsQEM6bABELEGASuxBwzpsQ4BK7A2Gro+B/A9ABUrCrADLg6wAsCxChn5BbALwLrB7fBtABUrCrAJLrELCgiwCsAOsQUG+QWwBMADALICBQouLi4BtgIDBAUJCgsuLi4uLi4usEAasQYBERKxCAw5OQAwMRMzEwEzARMzASMJASMw++IBFtQBE+D7/rDy/uv+5fMFsPu6BEb7uARI+lAEJ/vZAAAAAQApAAAE6QWwAAsAJgCyAAAAK7AIM7ICAgArsAUzAbAML7ENASsAsQIAERKxBAo5OTAxMwkBIQkBIQkBIQkBKQHD/kcBJAEyATIBJP5IAcL+2f7H/sYC3gLS/fICDv0u/SICFv3qAAABAAcAAATWBbAACAAwALIHAAArsgACACuwAzMBsAkvsAfWsQYM6bEKASuxBgcRErACOQCxAAcRErACOTAxEyEJASEBESMRBwEZAU8BTwEY/hj+BbD9TgKy/Gj96AIYAAABAFAAAASMBbAACQAuALIAAAArsQcD6bIEAgArsQMD6QGwCi+xCwErALEHABESsAE5sQQDERKwBjkwMTM1ASE1IRUBIRVQAvH9FAQf/Q4DCqQEQMyg+7rKAAAAAAEAhP68AhwGjgAHADUAsAcvsQUG6bAEL7ECBukBsAgvsADWtAcVAAoEK7ACMrEFEem0AxUACgQrsAYysQkBKwAwMRMRIRUjETMVhAGYpaX+vAfSvvmpvQABABT/gwNkBbAAAwARALIAAgArAbAEL7EFASsAMDETMwEjFPACYPAFsPnTAAEADP68AaYGjgAHAD4AsAcvsQAG6bADL7EEBukBsAgvsAfWsAMytAYVAAoEK7AGELEBEemwAS+wBhC0AxUACgQrsAMvsQkBKwAwMRczESM1IREhDKenAZr+ZocGV774LgAAAAABADUC2QM1BbAABgARALIBAgArAbAHL7EIASsAMDETATMBIwsBNQErqwEqzbOyAtkC1/0pAc3+MwAAAAABAAP/QQOYAAAAAwAaALIAAAArsQMH6bIAAAArAbAEL7EFASsAMDEzIRUhAwOV/Gu/AAAAAQAxBNECCQYAAAMAIACwAy+0AQsADgQrAbAEL7AA1rQCFQAJBCuxBQErADAxEyETIzEBFcPKBgD+0QAAAgBa/+wD+wROAB4AKQCCALIYAAArshwAACuxIgfpshABACuxCAbpsggQCiuzQAgMCSu0AyccEA0rsQME6QGwKi+wANaxHxHpsB8QsSUBK7AEMrEUEemxKwErsR8AERKwDDmwJRGyCxAcOTk5sBQSsRgaOTkAsSIYERKxFho5ObAnEbEUADk5sQgDERKwEzkwMRM0JDsBNTQmIyIGFSM0PgEzMhYXERQXFSMmJwYjIiY3FBYzMjY3NSMiBloBAe+VXmBTavN2y32+4gMp+BAMdKijzvNdTkh/IIOHiAEvrblHVGVTQFmbWL+t/hiSVxEfRnm6okZTRjvMXgAAAgB8/+wEMgYAAA8AGwBfALIAAAArsgwAACuxEgjpsgUBACuxGQjpsAEvAbAcL7AA1rEQEemwAjKxDw7psBAQsRUBK7EJEemxHQErsRAPERKwDjmwFRGxBQw5OQCxEgARErAOObEFGRESsAM5MDEzETMRNjMyEhEVFAIjIicHExYzMjY3NTQmIyIHfPNpssbi4cW+agwXQZ9yfAJ8dp5ABgD90nz+2v74Dvz+1ol1AT+NqqwfsLCKAAEAT//sA/UETgAcAFYAshoAACuxEgfpshIaCiuzQBIWCSuyBAEAK7ELB+myCwQKK7NACwcJKwGwHS+wANaxDxHpsA8QsRUBK7AIMrEWD+mwBzKxHgErsRUPERKxBBo5OQAwMRM1NAAzMhYXIy4BIyIGBxUUFjMyNjczDgIjIgBPAQjkwfMG5QR3XHaAAX94W3gE5QR2ynXj/vYCFRn3ASnht114q64nsK1qTmWvZgEmAAAAAAIAT//sBAMGAAAOABkAaQCyCQAAK7IMAAArsRII6bIDAQArsRcI6bAGLwGwGi+wANaxDxHpsA8QsRQBK7AFMrEIEemwCBCxCQ7psAkvsRsBK7EUDxESsQMMOTmwCRGwCjkAsRIJERKwCjmwFxGwADmwAxKwBTkwMRM0EjMyFxEzESMnBiMiAjcUFjMyNxEmIyIGT+jDrGrz3Axttr7r8391lUVDlXaAAiX6AS94Air6AHCEATLypbmFAc6CuwAAAAIAU//sBAsETgAVAB0ATwCyEwAAK7ENB+myBQEAK7EbB+m0FgoTBQ0rsRYF6QGwHi+wF9axCBDpshcICiuzQBcACSuxHwErsQgXERKxDxA5OQCxCg0RErEPEDk5MDETNTQSNjMyEhEVIR4BMzI3Fw4BIyIAEyE1LgEjIgZTfeKL3fH9PQudd6dpg0HZh+f+4fkBzwhyZWR7AgEeogD/jv7m/v5ihpyHfWFrASMBcxJ6fYwAAAEALQAAAtYGFQAUAFgAshMAACuyAQEAK7AOM7EABemwEDKwCy+xBgjpAbAVL7AT1rACMrESEemwDTKyEhMKK7NAEhAJK7ITEgors0ATAAkrsRYBKwCxCwERErAJObAGEbAIOTAxEzUzNTQ2MzIXByYjIh0BMxUjESMRLaXItEBIBig1rtzc8wOGtGO0xBK+CLNgtPx6A4YAAgBS/lYEDAROABkAJACEALIXAAArsR0I6bIGAQArsgMBACuxIgjpsAsvsREH6QGwJS+wANaxGhHpsBoQsRQBK7AfMrEIEemwCBCxBg7psAYvsSYBK7EaABESsQ4POTmwFBGzAxELFyQXObAGErAFOQCxEQsRErAOObAXEbAPObAdErAVObAiEbAAObAGErAFOTAxEzQSMzIXNzMRFAQjIiYnNxYzMjY9AQYjIgI3FBYzMjcRJiMiBlLtxLlqC9v+9+F34ztzcKR5jGmvvvHyhXaTR0WTeIUCJfwBLYFt++fV9mNQkoWDf0l1AS72o7t+Adx7vgAAAAABAHkAAAP4BgAAEABFALIAAAArsAgzsgUBACuxDQjpsAEvAbARL7AA1rEQEemwAjKwEBCxCQErsQgR6bESASuxCRARErAFOQCxBQ0RErADOTAxMxEzETYzIBMRIxE0JiMiBxF583e2AVoF82FekkgGAP3Eiv51/T0CunBdgvz7AAIAfQAAAZAF1QAJAA0APwCyCgAAK7ILAQArsAgvsQML6QGwDi+wANaxBRTpsQUU6bMKBQAIK7ENEemxDwErsQ0KERKzAwcIAiQXOQAwMRM0NjIWFRQGIiYTETMRfUeESEiERw/zBVM4Sko4N0lJ+uQEOvvGAAAAAAL/tf5LAYUF1QAMABYASwCyBQEAK7AKL7ECCOmwFS+xEAvpAbAXL7AE1rEHEemwEjKwBxCxDRTpsA0vsRgBK7EHBBESsQ8VOTkAsQIKERKwDDmwBRGwADkwMQcWMzI3ETMRFAYjIicTNDYyFhUUBiImSyYweQPzpZ9DPr1HhEhIhEfkCYQEo/tmpq8RBvc4Sko4N0lJAAAAAQB9AAAENgYAAAwAMACyAAAAK7AIM7IFAQArsAEvAbANL7AA1rEMEemwAjKxDgErALEFABESsQMKOTkwMTMRMxE3ASEJASEBBxF980wBKwEk/m4Bvf7n/r9sBgD8il8BUf49/YkB0G/+nwAAAQCMAAABfwYAAAMAHwCyAAAAK7ABLwGwBC+wANaxAxHpsQMR6bEFASsAMDEzETMRjPMGAPoAAAABAHwAAAZ5BE4AHQBwALIAAAArsQ0WMzOyAQEAK7IFAQArsAkzsRoI6bASMgGwHi+wANaxHRHpsAIysB0QsRcBK7EWEemwFhCxDgErsQ0R6bEfASuxHQARErADObAXEbAFObAWErAHObAOEbEJEjk5ALEBGhESsQMHOTkwMTMRMxc2MzIXNjMyFhcRIxE0JiMiBgcTIxEmIyIHEXzlB3LG2VB21rOvAvNaaFNpFQHzBb6SPQQ6cYWmpsbB/TkCwGdgWUj9GgLIv3f88AABAHkAAAP4BE4AEABNALIAAAArsAgzsgEBACuyBQEAK7ENCOkBsBEvsADWsRAR6bACMrAQELEJASuxCBHpsRIBK7EQABESsAM5sAkRsAU5ALEBDRESsAM5MDEzETMXNjMgExEjETQmIyIHEXnlB3jDAVIG81llk0gEOn2R/n39NQK9Z2OF/P4AAgBP/+wEPQROAA8AGgBAALINAAArsRMH6bIFAQArsRgH6QGwGy+wANaxEBHpsBAQsRUBK7EJEemxHAErsRUQERKxBQ05ObAJEbAHOQAwMRM1NBI2MzIAHwEUDgEjIgA3FBYyNjU0JiMiBk9+5JTbARELAXvlluX+7fOK9omNeXeMAhsMnwD/if7m6Tmg/IoBMfWnvcC5pMC9AAAAAgB8/mAEMAROAA8AGgBfALIMAAArsRIH6bIBAQArsgUBACuxGAjpsAAvAbAbL7AA1rEPEemwEDKxAg/psA8QsRUBK7EJEemxHAErsQ8CERKwAzmwFRGxDAU5OQCxEgwRErAOObEBGBESsAM5MDETETMXNjMyEhEVFAIjIicZARYzMjY1NCYjIgd84ApruMbh5MCya0KWdIOBeJVB/mAF2m6C/tn++g/7/tV1/f8CzH67vqK+ewAAAAIAT/5gBAIETgAOABkAaQCyDAAAK7ESB+myBgEAK7IDAQArsRcH6bAJLwGwGi+wANaxDxHpsA8QsQkBK7AUMrEIEemwCBCxBg3psAYvsRsBK7EJDxESsQMMOTmwBhGwBTkAsRIMERKwCjmwFxGwADmwBhKwBTkwMRM0EjMyFzczESMRBiMiAjcUFjMyNxEmIyIGT+jGtWoO2PNqqsLq84N0kEZGjnSFAib+ASp/a/omAfxwAS/2pr17Aex2ugAAAAEAfAAAArQETgANADQAsgAAACuyAQEAK7AHM7IFAQArsQoK6QGwDi+wANaxDRHpsAIysQ8BKwCxAQoRErADOTAxMxEzFzYzMhcHJiMiBxF86AZYnDQiATAzpzoEOnmNDuQIgP0cAAAAAQBL/+wDygROACYAbQCyIwAAK7EEBemyBCMKK7NABAAJK7IQAQArsRcF6bIXEAors0AXEwkrAbAnL7AN1rEaEOmwACDWEbEBEOmwGhCxBwErsBQysSAQ6bATMrEoASuxBxoRErQEChAdIyQXOQCxFwQRErENIDk5MDETMx4BMzI2NTQuAScmNTQ2MzIWFSM0JiMiBhUUFgQeARUUBiMiLgFL7AV4Y2Bka/hTtuy2wu/zaFZQZV4BHqNP8sSF0HQBVVZdSTtBRDQoWKeMvMCZRl1KPjg+P1d6V5K1YKgAAAABAAj/7AJyBUEAFABjALIRAAArsQwI6bIBAQArsAUzsQAF6bAHMrIBAAors0ABBAkrAbAVL7AT1rACMrEJEemwBDKyCRMKK7NACQcJK7AOMrITCQors0ATAAkrsRYBKwCxDBERErAPObAAEbAOOTAxEzUzETMRMxUjERQWMzI3FQYjIBkBCLLzv78xPyorU03+6AOGtAEH/vm0/aQ+Nwq8FwE1AmUAAAABAHf/7AP3BDoAEABNALILAAArsg4AACuxBQjpsgEBACuwCDMBsBEvsADWsQMR6bADELEHASuwCzKxChHpsRIBK7EHAxESsA45sAoRsAw5ALEFCxESsAw5MDETETMRFDMyNxEzESMnBiMiJnfzq7E+8+UGa8WwtQF9Ar39Rs5/Awn7xmp+zgAAAQAWAAAD2gQ6AAYAPQCyBgAAK7IAAQArsAMzAbAHL7AA1rEBDOmwARCxAwErsQQM6bEIASuxAwERErEFBjk5ALEABhESsAI5MDETMxsBMwEjFvzo5fv+idMEOvz6Awb7xgAAAAEAIQAABcwEOgAMAJEAsgwAACuxCQszM7IAAQArsgMEBjMzMwGwDS+wANaxARDpsAEQsQYBK7EHEOmxDgErsDYauj1L7ZYAFSsKsAMuDrACwLEKBfkFsAvAusK47YsAFSsKsAkusQsKCLAKwA6xBRj5BbAEwAMAsgIFCi4uLgG2AgMEBQkKCy4uLi4uLi6wQBqxBgERErEIDDk5ADAxEzMbATMbATMBIwsBIyHtr9634azt/tnI6OTIBDr9HQLj/RUC6/vGAuf9GQAAAAEAHwAAA+gEOgALACYAsgAAACuwCDOyAgEAK7AFMwGwDC+xDQErALECABESsQQKOTkwMTMJASEbASEJASELAR8BVv62AQzKzgEO/rUBVv702NcCJQIV/pwBZP3r/dsBcv6OAAABAAz+SwPWBDoADwBNALIAAQArsAMzsAcvsQsD6QGwEC+wANaxARPpsAEQsQMBK7EEE+mxEQErsQEAERKyBwkKOTk5sAMRsA85ALELBxESsAk5sAARsAI5MDETIRsBIQECIyInNRcyNj8BDAEG5dwBA/5SY+01QC5cXRsjBDr9IgLe+yL+7xK8A0NPXQAAAAABAFIAAAPABDoACQAuALIAAAArsQcH6bIEAQArsQMH6QGwCi+xCwErALEHABESsAE5sQQDERKwBjkwMTM1ASE1IRUBIRVSAiX95QNP/dUCQJ8C18Sa/SLCAAAAAAEAOP6YApEGPQAXADAAsAAvsQEF6QGwGC+wFdawAzKxEA/psAoysRkBK7EQFRESsA05ALEBABESsA05MDETNTI9AT4BNxcGBxUUBxYdARYXByQDNTQ4wQO1sDCtBq2tBq0w/p8HAhGy4tS03jKMOPrY4Vtc49X6OI1jAWDV4QAAAQCu/vIBVQWwAAMAIgCyAQIAKwGwBC+wANa0Aw0AFQQrtAMNABUEK7EFASsAMDETETMRrqf+8ga++UIAAQAb/pgCdQY9ABgAMACwEi+xEQXpAbAZL7AC1rAHMrEVD+mwDjKxGgErsRUCERKwBTkAsRESERKwBTkwMRc2EzU0NyY9AQInNx4BHQEUMxUiHQEUBgcbsAS2tgSwMLaywsKztds5AP/Q51ZW6s8A/zmMM+W5yOGy4cW75TMAAAABAHUBgwTcAy8AFwBiALAPL7EIA+myCA8KK7NACAsJK7AUL7EDA+myFAMKK7NAFAAJKwGwGC+wANa0Fw0AFQQrsBcQsQsBK7QMDQAVBCuxGQErsQsXERKxAw85OQCxCA8RErASObEDFBESsAY5MDETNDYzMh4CMzI2NTMUBiMiLgIjIgYVdbaUSoWRQydDVLy+jkp9mkMmQ00BqavbO4QicFSw3ziJIWhUAAAAAgCG/pQBmQRNAAsADwBBALIDAQArsQkL6QGwEC+wANawDDKxBhTpsQYU6bAPMrMOBgAIK7ENDemwDS+xDg3psREBK7EODRESsQkDOTkAMDETNDYzMhYVFAYjIiYbATMThkhCQUhIQUJIDBjRGAPLN0tLNzhLS/sBBAL7/gAAAAABAGT/CwQKBSYAIABvALAdL7QUCwAKBCuwDi+0BQsACgQrAbAhL7AA1rEREemwERCxHQErsAQysRwN6bAGMrAcELEXASuwCzKxGA/psAoysSIBK7EcHRESsQ4UOTkAsRQdERKxGx45ObAOEbIKFxg5OTmwBRKxBAc5OTAxEzU0Ejc1MxUeARcjLgEjIgMHFBYzMjY3Mw4BBxUjNSYCZMy3yJ65BOQHdlvmEAF/eVl4BuQExZLIt8wCEhzVASAi4eAc2Jxgdf7ISLCtaFCIzRzq6iIBHwAAAAABAF4AAAR8BcMAHwCTALIZAAArsRoD6bAWMrIGAgArsQwD6bIMBgors0AMCAkrtAABGQYNK7AQM7EACOmwEjIBsCAvsB/WsAIysRMM6bAQMrADINYRsQ8M6bIDDwors0ADAAkrsB8QsRQM6bIUHwors0AUEgkrsBMQsQkBK7EIEemxIQErsQ8fERKxBRY5ObEJFBESsAw5sAgRsAY5ADAxEzUzJzQ2IBYVIzQmIyIGFRchFSEXFAchByE1Mz4BNSdemwj6AZbo9WleWWcJATf+0AdAArgB++dSJysHAlbH8srq2rhfaYJo8sewh1XKyglvW7kAAgBd/+UFTwTxABsAKAB/ALIYAAArsRUbMzOxIAbpsCYvsQoG6QGwKS+wA9a0HA0AFQQrsBwQsSMBK7QRDQAVBCuxKgErsRwDERKzAQUHGyQXObAjEbMIDBYaJBc5sBESsw0PExUkFzkAsSAYERKzFAAWGiQXObAmEbMBBQ8TJBc5sAoSswYIDA4kFzkwMT8BJjU0Nyc3FzYzMhc3FwcWFRQHFwcnBiMiJwcTFB4BMj4BNC4BIg4BXYdkbZCNjpvAwpuRjpRrYouOhJ/Lyp6BT26+3L5tbb3evm12iZzFyKWTkJFzdZSRl5/KwZyNkYZ/foQCenjOdXbO7sx1dcwAAAEACwAABDQFsAAWAHQAsg4AACuyAAIAK7ADM7QQEQ4ADSuwCTOxEATpsAsytBQVDgANK7AFM7EUBOmwBzIBsBcvsA7WsBIysQ0M6bAIMrINDgors0ANBwkrsAoysg4NCiuzQA4UCSuwEDKxGAErsQ0OERKwAjkAsQAVERKwAjkwMRMhCQEhATMVIRUhFSERIxEhNSE1ITUzCwERAQUBBgEN/qvq/tEBL/7R/P7MATT+zPgFsP2fAmH9NpiKl/7TAS2XipgAAAAAAgCI/vIBbQWwAAMABwAiALIFAgArAbAIL7AA1rAEMrEDD+mwBjKxAw/psQkBKwAwMRMRMxEDETMRiOXl5f7yAxv85QPIAvb9CgAAAAIAWv4mBIwFxAAvAD0AlACyFgIAK7EdB+myHRYKK7NAHRkJK7AtL7EEB+kBsD4vsA7WsAAysTAR6bABMrATINYRsSAR6bAwELE3ASuxJhDpsCYQsCog1hGxBxHpsAcvsBozsSoR6bEZEemxPwErsTATERKwEDmxByAREkAJBAsWHSMtNTo8JBc5sSo3ERKwKDkAsR0EERK1AAETKjU8JBc5MDEXNxQWMzI2NTQmJy4CNTQ3LgE1NCQzMgQVIzQmIyIGFRQWBB4BFRQHFhUUBCMiJBMUFh8CNjU0JicmJwZa8pyIeY2Gu7y+XalBRAET5vABDPOReHuLeAGDwlqrh/7y6vb+4PZjlbMuc4i7UUxsMgFueF9PTVs3M26abbhaMohkqszhzGqAX1JUV2hxmWy4WWS5rcbZAy9RVi81EC91UWE4FRwoAAACAF0E3wMjBcwACAARADkAsAcvsA8zsQMK6bALMrEDCukBsBIvsADWsQUM6bAFELEJASuxDgzpsRMBKwCxAwcRErEJDjk5MDETNDYyFhQGIiYlNDYyFhQGIiZdQ3ZERHZDAclDdkREdkMFVjJERGRERDEyRERkREQAAAAAAwBX/+wF4gXEAA0AGwA2ALgAsgoAACu0EgQADwQrsgQCACu0GQQADwQrtDUuCgQNK7Q1BAAPBCuyLjUKK7NALjIJK7QgJwoEDSu0IAQADwQrsicgCiuzQCcjCSsBsDcvsADWtA8NAA0EK7APELEcASu0Kw0ADQQrsCsQsTEBK7AkMrQyDQANBCuwIzKwMhCxFQErtAcNAA0EK7E4ASuxMSsREkAJAxESGQonIDQ1JBc5sDIRsAQ5ALEnLhEStQYHDg8VACQXOTAxEzQSJCAEEhACBCMiJAISEBIEICQSNTQCJCMiBBM1NDYzMhYVIzQmIyIGHQEUFjMyNjUzFAYgJle7AUsBgAFKu7v+uMLB/re8epsBEQFAAROYlv7uo5/+70W/nqOtnFxYXGdoW1lanK/+wL0C2coBWsfH/qb+bP6mycgBWgF1/qz+4KeqASCnpgEdq6T+AHGu1aWVYFOIdnV2hlFimKLVAAAAAAIAjQKzAxEFxAAaACQAgQCyDgIAK7EHBOmwGC+xHQTpsCIvtAMEAA8EKwGwJS+wANa0Gw0AFQQrsAoysBsQtAsNABUEK7ALL7AbELEgASuwBDK0Eg0AFQQrsSYBK7EgGxESsQ4YOTmwEhGxFRY5OQCxHRgRErEUFjk5sCIRsRIAOTmxBwMRErIKCxE5OTkwMRM0NjsBNTQjIgYVJzQ2MzIWFREUFyMnBiMiJjcUMzI2NzUjDgGNqK1mdEFJra+IiZoasRFNfHaDr3UoVBtqTFYDl255M38zMA5ogZGE/sRhUURSe21YJBmJATwAAgBXAIoDhQOpAAYADQAAEzUBMwMTIxM1ATMDEyNXASCn9/enRwEgp/f3pwIQEwGG/nD+cQGGEwGG/nD+cQAAAAEAfwF2A8IDJQAFADAAsAAvsQEF6bIAAQors0AABAkrAbAGL7AE1rEDDemyBAMKK7NABAAJK7EHASsAMDETNSERIxF/A0PIAnqr/lEBBAAAAQBHAgkCVALNAAMAIgCwAC+xAQfpsQEH6QGwBC+xAAErtAMVAAgEK7EFASsAMDETNSEVRwINAgnExAAABABX/+wF4gXEAA0AGwAxADoAygCyCgAAK7QSBAAPBCuyBAIAK7QZBAAPBCu0MDIKBA0rtDAEAA8EK7IwMgors0AwHAkrsCkytB46CgQNK7QeBAAPBCsBsDsvsADWtA8NAA0EK7APELEcASu0MQ0ADQQrsDIysDEQsTYBK7AqMrQhDQANBCuwKDKwIRCxFQErtAcNAA0EK7E8ASuxMRwRErEDETk5sDYRshIZCjk5ObAhErMEIyUmJBc5ALEwEhESsgcPJTk5ObAyEbIVACM5OTmwOhKyBg4hOTk5MDETNBIkIAQSEAIEIyIkAhIQEgQgJBI1NAIkIyIEExEhMhYVFAceARQWFxUjJjU0JisBGQEzMjY1NCYnI1e7AUsBgAFKu7v+uMLB/re8epsBEQFAAROYlv7uo5/+74kBGZmseEE0BwqbDUJNno9FXUddjQLZygFax8f+pv5s/qbJyAFaAXX+rP7gp6oBIKemAR2rpPyZA1KHfXU/HW+jRBcQIqBMQ/6vAdc+NkY7AQAAAQCbBQwDSgWqAAMAFwCwAC+xAQTpsQEE6QGwBC+xBQErADAxEzUhFZsCrwUMnp4AAgB/A68CiwXEAAkAEwBUALIDAgArsRME6bINAQArsQgE6bIAAAArsgYAACsBsBQvsAHWtAsNAA0EK7ALELEQASu0Bg0ADQQrsRUBK7EQCxESsQgDOTkAsRMNERKxAQU5OTAxEjQ2MzIWFAYjIgIUFjMyNjU0JiJ/nWtqmphsbRBJNDVFRWoEStyentybAT1oSEc1NEwAAAACAF8AAQPzBPwACwAPAFsAsgwAACuxDQfpsAAvsAczsQEI6bAFMrIAAQors0AACgkrsgEACiuzQAEDCSsBsBAvsArWsAIysQkN6bAEMrIJCgors0AJBwkrsgoJCiuzQAoACSuxEQErADAxEzUhETMRIRUhESMRATUhFV8BZdgBV/6p2P65A1ECvMcBef6Hx/58AYT9RcTEAAEAPAKbArIFuwAXAG8AsgMCACuxFATpshQDCiuzQBQACSuwDS+xCgTpAbAYL7AA1rQXDQAVBCuwFxCxEQErtAYNABUEK7IGEQors0AGDAkrshEGCiuzQBENCSuxGQErsREXERKxAwo5OQCxCg0RErAOObAUEbEGETk5MDETNDYzMhYVFA8CIRUhNQE2NTQmIyIGFTyph4+camKMAXP9nAEdcTY0OkIErnSZgHNrZldxlH0BBWdDKjVCNgAAAQA3ApACqQW7ACQAjwCyGAIAK7ERBOmyERgKK7NAERUJK7AiL7EEBOmyBCIKK7NABAAJK7AKL7QLBAAPBCsBsCUvsADWsBUytAENABUEK7AUMrABELEHASuwDjK0Hw0AFQQrsBsysgcfCiuzQAcKCSuxJgErsQcBERKxGCI5ObAfEbAdOQCxCgQRErAfObALEbAdObARErAbOTAxEzMUFjMyNjU0JyM1MzI1NCYjIgYVIzQ2MzIWFRQHFhUUBiMiJje6RTw/PYZcUYQ2PjBBuqWCj6OHlbGPh6sDgCY1NyplAYFhIzUnI2N8eWl3MymOan5/AAEAcATRAkgGAAADACAAsAAvtAELAA4EKwGwBC+wANa0AhUACQQrsQUBKwAwMRsBIQFwwwEV/usE0QEv/tEAAAABAJL+YAQfBDoAEgBSALIMAAArsg8AACuxBgfpsgEBACuwCTOwAC8BsBMvsADWsRIR6bACMrASELEIASuxCxHpsRQBK7EIEhESsA85sAsRsA05ALEGDBESsQ0ROTkwMRMRMxEeATMyNxEzESMnBiMiJxGS8gJZaqg7898HXJN5Tf5gBdr9hI2CeQMS+8ZWazf+PgAAAQBFAAADVgWwAAoANwCyBgAAK7IDAgArAbALL7AA1rQEFQAHBCuwBBCxBg3psAYvsAQQtAAVAAcEK7AAL7EMASsAMDETNAAzIREjESMiJEUBCuYBIdJQ5v73A9zVAP/6UAII/gAAAAABAI4CRQGpA1IACgAiALAIL7EDC+mxAwvpAbALL7AA1rEFFemxBRXpsQwBKwAwMRM0NjIWFRQGIyImjkqGS05AQUwCyjpOTjo7SkoAAQBt/kEByQADAA4APACwCC+0CQQADwQrsAAvsQEE6QGwDy+wDNaxBQ3psRABK7EFDBESsQMCOTkAsQAJERKwBTmwARGwAzkwMRc3MwcWFRQGIycyNjU0Jm0gsQuWrJsHQkdHiIs2G5JpdokvKi0jAAEAgAKbAgIFrgAGAEMAsAAvsQEE6bIBAAors0ABAgkrAbAHL7AF1rQEDQAVBCuyBQQKK7NABQEJK7EIASuxBAURErACOQCxAQARErAGOTAxEzUlMxEjEYABbxO5BKWSd/ztAjoAAAAAAgB3ArIDLAXEAAwAGgBAALIEAgArsRcE6bAKL7EQBOkBsBsvsADWtA0NABUEK7ANELETASu0Bw0AFQQrsRwBK7ETDRESsgMECjk5OQAwMRM1NDYgFh0BFAYjIiY3FBYzMjY3NTQmIyIGFXe/ATbAvJ2evq9dUE5bAV1PTl0EGUigw8KmSJ/DxJ5ibmxhUGFubWYAAAIAXQCKA5kDqQAGAA0AADcTAzMBFQEzEwMzARUBXff3pwEg/uDO9/enASD+4IoBjwGQ/noT/noBjwGQ/noT/noAAAAABABZAAAFgwWrAAYACgAVABkAsACyEwAAK7AVL7AQM7EWBOmwDjKyFhUKK7NAFgwJK7AAL7EBBOmwCDKyAQAKK7NAAQIJKwGwGi+wBda0BA0AFQQrsgUECiuzQAUBCSuwBBCxEwErsBcytBINABUEK7ANMrITEgors0ATCwkrsRsBK7EEBRESsgIHCjk5ObATEbIIDBY5OTmwEhKwCTkAsRUTERKwCjmwFhGxBws5ObAAErIEBRg5OTmwARGxBgk5OTAxEzUlMxEjERMBFwElATMRMxUjFSM1ITczNQdZAW8TuSYCx339OQE1AW29X1+7/pqsug4EopJ3/O0COvvrBHJI+46nAfn+JZejo5fyFgADAFAAAAXMBa4ABgAKACIAxwCyGAAAK7EVBOmwHy+xDgTpsh8OCiuzQB8LCSuwAC+xAQTpsgEACiuzQAECCSsBsCMvsAXWsAcytAQNABUEK7IFBAors0AFAQkrsAQQsQsBK7QiDQAVBCuwIhCxHAErtBENABUEK7IRHAors0ARFwkrshwRCiuzQBwYCSuxJAErsQQFERKxAgo5ObEiCxESsAg5sBwRsg4VCTk5OQCxFRgRErEKGTk5sB8RsgcRHDk5ObAOErEFBDk5sQEAERKyBggJOTk5MDETNSUzESMREwEXCQE0NjMyFhUUDwIhFSE1ATY1NCYjIgYVUAFvE7kEAsd9/TkBvKmHj5xqYowBc/2cAR1xNjQ6QgSlknf87QI6++gEckj7jgGedJmAc2tmV3GUfQEFZ0MqNUI2AAAAAAQAZwAABfwFuwAkACgAMwA3AQkAsjEAACuyGAIAK7ERBOmyERgKK7NAERUJK7QzNDEYDSuwLDOxMwTpsC4ysjQzCiuzQDQqCSu0IgQxGA0rsSIE6bIEIgors0AEAAkrtAsKMRgNK7QLBAAPBCsBsDgvsADWsBUytAENABUEK7AUMrABELEHASuwDjK0Hw0AFQQrsBsysgcfCiuzQAcKCSuwHxCxMQErsDUytDANABUEK7ArMrIxMAors0AxKQkrsTkBK7EHARESshgiJTk5ObAfEbEdKDk5sDESsiYqNDk5ObAwEbAnOQCxMzERErAoObA0EbElKTk5sCISsDY5sQoEERKwHzmwCxGwHTmwERKxGyc5ObAYEbAmOTAxEzMUFjMyNjU0JyM1MzI1NCYjIgYVIzQ2MzIWFRQHFhUUBiMiJgkBFwElATMRMxUjFSM1ITczNQdnukU8Pz2GXFGENj4wQbqlgo+jh5Wxj4erAW4Cx339OQEhAW29X1+7/pqsug4DgCY1NyplAYFhIzUnI2N8eWl3MymOan5//a4Eckj7jqcB+f4ll6Ojl/IWAAAAAAIAQv5/A6UETgAZACMAgwCyAAAAK7ENEzMzsh0BACuxIgvpsBcvsRAD6QGwJC+wANaxDRHpsA0QsQUBK7EHD+mwBxCzLQcfDiuxGhTpsBovsR8U6bAHELETASuxFBHpsSUBK7ENABESsAI5sBoRsAM5sAUSsQQLOTmwBxG2ChAXHB0hIiQXOQCxIgARErAGOTAxMzQ/ATY/ATMOAQ8BBhUUFjMyNjUzDgEjIiYBNDYyFhUUBiImQptcTgoC4wI1SWdaYllYavMC78LO4gE1SIRHR4RIpaNdSHM1fJFPamFqXl1kU7HQyQSEN0tLNzhLSwAAAAADABIAAAVCBzYABwALAA4ALACyAAAAK7ADM7IBAgArtAYMAAENK7EGA+kBsA8vsRABKwCxAQwRErAOOTAxMwEzASEDIQMTIRMjAyEDEgIm4wIn/vh3/cx2OwEVw8qMAabTBbD6UAFT/q0HNv7R/BgCXAAAAAMAEgAABUIHNgAHAAoADgAsALIAAAArsAMzsgECACu0BggAAQ0rsQYD6QGwDy+xEAErALEBCBESsAo5MDEzATMBIQMhAxMhCwETIQESAibjAif++Hf9zHa9AabTd8MBFf7rBbD6UAFT/q0CHwJcAYwBL/7RAAAAAAMAEgAABUIHNwAHABAAEwAsALIAAAArsAMzsgECACu0BhEAAQ0rsQYD6QGwFC+xFQErALEBERESsBM5MDEzATMBIQMhAxM1ATMBFSMnBwMhAxICJuMCJ/74d/3Mdj4BD48BEcOWlUIBptMFsPpQAVP+rQYWDQEU/uoLnJz8CQJcAAAAAAMAEgAABUIHLAAHAB0AIAB6ALIAAAArsAMzsgECACu0Bh4AAQ0rsQYD6bAVL7EOBOmzGg4VCCuxCwTpAbAhL7AI1rQdDQANBCuwHjKwHRCxEQErtBINAA0EK7EiASuxHQgRErAGObAREbQBCwIVHyQXObASErAFOQCxAR4RErAgObAVEbEIHTk5MDEzATMBIQMhAxM0NjMyFjMyNjUXFAYjIi4CIyIGFRMhAxICJuMCJ/74d/3MdiZ/XzmhNCY2lX9gJzlpKxomNQIBptMFsPpQAVP+rQYabpZaOS8MbpIRPAw5LvwNAlwAAAAABAASAAAFQgcCAAcAEAATABwAcQCyAAAAK7ADM7IBAgArtAYRAAENK7EGA+mwDy+wGjOxCwrpsBYyAbAdL7AI1rENDOmwDRCxFAErsRkM6bEeASuxDQgRErIBBhE5OTmwFBGwEzmwGRKyAgUSOTk5ALEBERESsBM5sQsPERKxFBk5OTAxMwEzASEDIQMTNDYyFhQGIiYTIQMTNDYyFhQGIiYSAibjAif++Hf9zHYyQ3ZERHZDiwGm02tDdkREdkMFsPpQAVP+rQaMMkREZERE+8UCXAIQMkREZEREAAQAEgAABUIHlAAHABEAFAAfAIAAsgAAACuwAzOyAQIAK7QGEgABDSuxBgPpsBAvtBgEAA8EK7AeL7QLBAAPBCsBsCAvsAnWtBUNAA0EK7AVELEbASu0Dg0ADQQrsSEBK7EVCRESsQESOTmwGxGzAhAUCyQXObAOErATOQCxARIRErAUObEeGBESswgNDgkkFzkwMTMBMwEhAyEDEjQ2MzIWFAYjIgMhCwEUFjMyNjU0JiIGEgIm4wIn/vh3/cx2t39fXYB9YGF3AabTa0IuL0E/Yj8FsPpQAVP+rQZvqnt7qnj8KAJcAkkvQUAwLkNDAAL/9gAAB1cFsAAPABIAfACyDAAAK7AAM7EJB+myAQIAK7EECOm0DhAMAQ0rsQ4J6bQFCAwBDSuxBQjpAbATL7AS1rEEEemwBBCwCCDWEbEREOmwES+wDTOxCBDpsAUysQkM6bIJEQors0AJBwkrs0AJCgkrsRQBK7EEERESsAw5ALEEBRESsBI5MDEjASEVIRMhFSETIRUhAyEDASEDCgNDA+D9ehECJP3kFAKX/H4P/gq4ASwBeRsFsMX+aMX+NsQBVP6sAisCiAAAAAIAZv48BOsFxAAdACwAigCyGgAAK7QfBAAPBCuyBQIAK7EMA+myDAUKK7NADAkJK7AmL7QnBAAPBCsBsC0vsADWsRAM6bAQELEqASuxIw3psCMQsRYBK7AJMrEXDOmwCDKxLgErsSoQERK3DAUTGh4fJickFzmwIxGxISA5OQCxGicRErIeISM5OTmxDB8RErITFhc5OTkwMRM1NBIkMzIAFyMuASMiBgcVFBYzMjY3MwYAIyIkAgE3MwcWFRQGIycyNjU0JmaSARGz8QEmGPwSk46lsQKpo5WWFPwW/tT5rv73kAHNILELlqybB0JHRwKKiM4BOqr++u+di/Hpgez4hpzp/vulATD9sos2G5JpdokvKi0jAAACAJQAAARMBz0ACwAPAE8AsgAAACuxCQPpsgECACuxBAPptAUIAAENK7EFCOkBsBAvsADWsQkM6bAEMrIJAAors0AJAwkrsAoys0AJBwkrsREBK7EJABESsAw5ADAxMxEhFSERIRUhESEVASETI5QDsf1MAlb9qgK7/M0BFcPKBbDM/m7I/kDKBz3+0QAAAAACAJQAAARMBz0ACwAPAEcAsgAAACuxCQPpsgECACuxBAPptAUIAAENK7EFCOkBsBAvsADWsQkM6bAEMrIJAAors0AJAwkrsAoys0AJBwkrsREBKwAwMTMRIRUhESEVIREhFQETIQGUA7H9TAJW/aoCu/2rwwEV/usFsMz+bsj+QMoGDgEv/tEAAgCUAAAETAc+AAsAFABRALIAAAArsQkD6bIBAgArsQQD6bQFCAABDSuxBQjpAbAVL7AA1rEJDOmwBDKyCQAKK7NACQMJK7AKMrNACQcJK7EWASuxCQARErEMDTk5ADAxMxEhFSERIRUhESEVATUBMwEVIycHlAOx/UwCVv2qArv80AEPjwERw5aVBbDM/m7I/kDKBh0NART+6gucnAAAAAMAlAAABEwHCQALABQAHQCHALIAAAArsQkD6bIBAgArsQQD6bQFCAABDSuxBQjpsBMvsBszsQ8K6bAXMgGwHi+wANaxCQzpsAQysgkACiuzQAkDCSuwCjKzQAkHCSuwABCwDCDWEbERDOmwCRCxFQErsRoM6bEfASuxCQwRErEOEzk5sBERsQ8SOTkAsQ8TERKxFRo5OTAxMxEhFSERIRUhESEVATQ2MhYUBiImJTQ2MhYUBiImlAOx/UwCVv2qArv8xEN2RER2QwHJQ3ZERHZDBbDM/m7I/kDKBpMyRERkREQxMkREZEREAAAAAv/IAAABoAc9AAMABwAqALIEAAArsgUCACsBsAgvsATWsQcM6bACMrEJASuxBwQRErEDATk5ADAxAyETIwMRMxE4ARXDyjP8Bz3+0fnyBbD6UAAAAgCjAAACfQc9AAMABwAqALIAAAArsgECACsBsAgvsADWsAQysQMM6bEJASuxAwARErEFBzk5ADAxMxEzEQMTIQGj/PrDARX+6wWw+lAGDgEv/tEAAv/LAAACegc+AAgADAApALIJAAArsgoCACsBsA0vsAnWsQwM6bEOASuxDAkRErIDAgc5OTkAMDEDNQEzARUjJwcTETMRNQEPjwERw5aVF/wGHQ0BFP7qC5yc+eMFsPpQAAAAAAP/vwAAAoUHCQAIAAwAFQBjALIJAAArsgoCACuwBy+wEzOxAwrpsA8yAbAWL7AJ1rEMDOmzBQwJCCuxAAzpsAAvsQUM6bMNDAkIK7ESDOmxFwErsQkAERKxAwY5ObESDBESsQ8UOTkAsQMHERKxDRI5OTAxAzQ2MhYUBiImExEzEQM0NjIWFAYiJkFDdkREdkPk/BdDdkREdkMGkzJERGRERPmfBbD6UAaSMkREZEREAAAAAAL/9wAABPAFsAAPAB0AXQCyDQAAK7EQA+myBAIAK7EZA+m0AQANBA0rsBwzsQEF6bAaMgGwHi+wDtawAjKxEAzpsBkyshAOCiuzQBAcCSuyDhAKK7NADgAJK7AQELEUASuxCQzpsR8BKwAwMQM1MxEhMgQSHQEUAgQjIRETMzI2PQE0JisBETMVIwm7Aa7BASukpf7Pxf5d/aPL1c7EseXlAoyqAnqs/sTMSc/+xqoCjP4+/fBG7fr+UqoAAgCUAAAFFwcsAAkAHwCNALIAAAArsAYzsgECACuwBDOwFy+xEATpsxwQFwgrsQ0E6QGwIC+wANaxCQzpswoJAAgrtB8NAA0EK7AJELEDASuxBgzpsxQGAwgrtBMNAA0EK7ATL7QUDQANBCuxIQErsQkKERKwAjmxEx8RErENFzk5sAMRsAc5ALEBABESsQMIOTmwFxGxCh85OTAxMxEzAREzESMBEQM0NjMyFjMyNjUXFAYjIi4CIyIGFZT9Aov7/f13KX9fOaE0JjaVf2AnOWkrGiY1BbD78wQN+lAECfv3Bhpullo5LwxukhE8DDkuAAAAAAMAZv/sBR4HNgAQAB4AIgA+ALINAAArsRQJ6bIFAgArsRsJ6QGwIy+wANaxEQzpsBEQsRcBK7EJDOmxJAErsRcRERK0BQQNHyEkFzkAMDETNTQSJCAEEhcVFAIEIyIkAjcUEjMyEj0BNAIjIgIHEyETI2aXARMBZAETlgGU/u2zsf7rl/y7pqi1t6ikuQIIARXDygKqUtUBRq2r/r/VUdb+va2tAUDZ8P76AQD2TPIBAv7/6wQw/tEAAAAAAwBm/+wFHgc2ABAAHgAiAD4Asg0AACuxFAnpsgUCACuxGwnpAbAjL7AA1rERDOmwERCxFwErsQkM6bEkASuxFxERErQFBA0fISQXOQAwMRM1NBIkIAQSFxUUAgQjIiQCNxQSMzISPQE0AiMiAgcbASEBZpcBEwFkAROWAZT+7bOx/uuX/LumqLW3qKS5AubDARX+6wKqUtUBRq2r/r/VUdb+va2tAUDZ8P76AQD2TPIBAv7/6wMBAS/+0QADAGb/7AUeBzcAEAAeACcAPgCyDQAAK7EUCemyBQIAK7EbCekBsCgvsADWsREM6bARELEXASuxCQzpsSkBK7EXEREStAUEDR8jJBc5ADAxEzU0EiQgBBIXFRQCBCMiJAI3FBIzMhI9ATQCIyICBxM1ATMBFSMnB2aXARMBZAETlgGU/u2zsf7rl/y7pqi1t6ikuQILAQ+PARHDlpUCqlLVAUatq/6/1VHW/r2trQFA2fD++gEA9kzyAQL+/+sDEA0BFP7qC5ycAAMAZv/sBR4HLAAQACYANAB/ALINAAArsSoJ6bIFAgArsTEJ6bAeL7EXBOmzIxceCCuxFATpAbA1L7AA1rEnDOmzEScACCu0Jg0ADQQrsCcQsS0BK7EJDOmzGwktCCu0Gg0ADQQrsBovtBsNAA0EK7E2ASuxGiYRErYEBRQNHioxJBc5ALEeBRESsREmOTkwMRM1NBIkIAQSFxUUAgQjIiQCEzQ2MzIWMzI2NRcUBiMiLgIjIgYVAxQSMzISPQE0AiMiAgdmlwETAWQBE5YBlP7ts7H+65fvf185oTQmNpV/YCc5aSsaJjWIu6aotbeopLkCAqpS1QFGrav+v9VR1v69ra0BQARBbpZaOS8MbpIRPAw5Lvyg8P76AQD2TPIBAv7/6wAEAGb/7AUeBwIAEAAZACcAMACCALINAAArsR0J6bIFAgArsSQJ6bAYL7AuM7EUCumwKjIBsDEvsADWsRoM6bMRGgAIK7EWDOmwGhCxIAErsQkM6bMtCSAIK7EoDOmwKC+xLQzpsTIBK7EWGhESshMEGDk5ObAoEbINHSQ5OTmwIBKyBSsuOTk5ALEUGBESsSgtOTkwMRM1NBIkIAQSFxUUAgQjIiQCEzQ2MhYUBiImExQSMzISPQE0AiMiAgcBNDYyFhQGIiZmlwETAWQBE5YBlP7ts7H+65f7Q3ZERHZDAbumqLW3qKS5AgHIQ3ZERHZDAqpS1QFGrav+v9VR1v69ra0BQASzMkREZERE/Fjw/voBAPZM8gEC/v/rA4UyRERkREQAAQBNANYD7ASGAAsAABMJATcJARcJAQcJAU0BPP7ElAE7ATyU/sQBPJT+xP7FAWwBQgFClv6+AUKW/r7+vpYBQf6/AAADAGn/oQUiBe4AFwAgACkAZQCyEQAAK7EjCemyBQIAK7EdCekBsCovsADWsRgM6bAYELEmASuxDQzpsSsBK7EYABESsBQ5sCYRtQcREwUbISQXObANErAIOQCxIxERErETFjk5sB0RsRopOTmwBRKxBwo5OTAxEzU0EiQzMhc3MwcWExUUAgQjIicHIzcmExQXASYjIgIHExYzMhI9ATQnaZYBFLLFj1enk50BlP7ttKSEW6mRw/1HAfZXh6S5AqpOaam1LAK5Q9UBRK9lj/PB/sNL1v69rUuW7sMBYM+AAzpV/v/r/ew2AQD2TKZyAAACAH3/7AS9BzYAEAAUAEIAsg4AACuxBgPpsgECACuwCTMBsBUvsADWsQMM6bADELEIASuxCwzpsRYBK7EDABESsBE5sAgRsw4SExQkFzkAMDETETMRFBYzIBkBMxEUACMiABMhEyN9/JSQAST8/tf3+v7axQEVw8oB5APM/DKSmgE0A8b8M+j+8QELBj/+0QACAH3/7AS9BzYAEAAUAEIAsg4AACuxBgPpsgECACuwCTMBsBUvsADWsQMM6bADELEIASuxCwzpsRYBK7EIAxESsw4REhQkFzmwCxGwEzkAMDETETMRFBYzIBkBMxEUACMiAAETIQF9/JSQAST8/tf3+v7aAaPDARX+6wHkA8z8MpKaATQDxvwz6P7xAQsFEAEv/tEAAgB9/+wEvQc3ABAAGQBNALIOAAArsQYD6bIBAgArsAkzAbAaL7AA1rEDDOmwAxCxCAErsQsM6bEbASuxAwARErEREjk5sAgRtA4TFBcZJBc5sAsSsRUWOTkAMDETETMRFBYzIBkBMxEUACMiABM1ATMBFSMnB338lJABJPz+1/f6/trIAQ+PARHDlpUB5APM/DKSmgE0A8b8M+j+8QELBR8NART+6gucnAAAAAMAff/sBL0HAgAQABkAIgB7ALIOAAArsQYD6bIBAgArsAkzsBgvsCAzsRQK6bAcMgGwIy+wANaxAwzpsxEDAAgrsRYM6bADELEIASuxCwzpsx8LCAgrsRoM6bAaL7EfDOmxJAErsRYDERKxExg5ObAaEbEOBjk5sAgSsR0gOTkAsRQYERKxGh85OTAxExEzERQWMyAZATMRFAAjIgATNDYyFhQGIiYlNDYyFhQGIiZ9/JSQAST8/tf3+v7avEN2RER2QwHJQ3ZERHZDAeQDzPwykpoBNAPG/DPo/vEBCwWVMkREZEREMTJERGRERAAAAAIABwAABNYHNgAIAAwANwCyBwAAK7IAAgArsAMzAbANL7AH1rAJMrEGDOmxDgErsQYHERKyAgoMOTk5ALEABxESsAI5MDETIQkBIQERIxEbASEBBwEZAU8BTwEY/hj+B8MBFf7rBbD9TgKy/Gj96AIYA+8BL/7RAAIAlAAABH4FsAAMABQASwCyAAAAK7IBAgArtAsNAAENK7ELB+m0AxQAAQ0rsQMH6QGwFS+wANaxDBHpsQINMjKwDBCxEQErsQcR6bEWASsAsRQNERKwBzkwMTMRMxEzMgQVFAQrARkBMzI2NCYnI5Tz8fQBEv7u8/L2fZGMev4FsP7o7sjH7/7UAe+C3oQCAAEAiP/sBJsGFQAsAIkAsgAAACuyFAAAK7EbB+mwKS+xBAfpAbAtL7AA1rEsEemwLBCxJgErsQcQ6bMMByYIK7EjEemwIy+xDBHpsx4HJggrsRER6bEuASuxIywRErMEGBcpJBc5sCYRsCE5sAwSsRQbOTmwHhGwCjmxEQcRErAPOQCxGwARErAXObApEbIHERg5OTkwMTMRNDYzMhYVFA4CFRQeAhUUBiMiJic3HgEzMjY1NC4CNTQ2NTQmIyIHEYjlzrvXG0UWQbJR2cZQqyYxLX82YVpGrlF+XFC4BARR1u67qT5icUEnLFSUiUuruScZwxwlVkMxW4iIUFjJTVFh9/ukAAAAAAMAWv/sA/sGAAAeACIALQCSALIYAAArshwAACuxJgfpshABACuxCAbpsggQCiuzQAgMCSu0AyscEA0rsQME6bAfLwGwLi+wANaxIxHpsCMQsSkBK7AEMrEUEemxLwErsSMAERKxDB85ObApEbULEBwgISIkFzmwFBKxGBo5OQCxJhgRErEWGjk5sCsRsRQAOTmxCAMRErATObEfEBESsCE5MDETNCQ7ATU0JiMiBhUjND4BMzIWFxEUFxUjJicGIyImEyETIwMUFjMyNjc1IyIGWgEB75VeYFNq83bLfb7iAyn4EAx0qKPOhAEVw8qfXU5IfyCDh4gBL625R1RlU0BZm1i/rf4YklcRH0Z5ugVa/tH8d0ZTRjvMXgAAAwBa/+wD+wYAAB4AKQAtAJIAshgAACuyHAAAK7EiB+myEAEAK7EIBumyCBAKK7NACAwJK7QDJxwQDSuxAwTpsCsvAbAuL7AA1rEfEemwHxCxJQErsAQysRQR6bEvASuxHwARErAMObAlEbULEBwqKy0kFzmwFBKyGBosOTk5ALEiGBESsRYaOTmwJxGxFAA5ObEIAxESsBM5sSsQERKwKjkwMRM0JDsBNTQmIyIGFSM0PgEzMhYXERQXFSMmJwYjIiY3FBYzMjY3NSMiBhsBIQFaAQHvlV5gU2rzdst9vuIDKfgQDHSoo87zXU5IfyCDh4hvwwEV/usBL625R1RlU0BZm1i/rf4YklcRH0Z5uqJGU0Y7zF4DMwEv/tEAAAAAAwBa/+wD+wYBAB4AJwAyAJgAshgAACuyHAAAK7ErB+myEAEAK7EIBumyCBAKK7NACAwJK7QDMBwQDSuxAwTpsCEvAbAzL7AA1rEoEemwKBCxLgErsAQysRQR6bE0ASuxKAARErIMHyA5OTmwLhG2CxAcISIlJyQXObAUErMYGiMkJBc5ALErGBESsRYaOTmwMBGxFAA5ObEIAxESsBM5sSEQERKwHzkwMRM0JDsBNTQmIyIGFSM0PgEzMhYXERQXFSMmJwYjIiYTNQEzARUjJwcDFBYzMjY3NSMiBloBAe+VXmBTavN2y32+4gMp+BAMdKijzocBD48BEcOWlVVdTkh/IIOHiAEvrblHVGVTQFmbWL+t/hiSVxEfRnm6BDoNART+6gucnPxoRlNGO8xeAAMAWv/sA/sF9gAeADQAPwDYALIYAAArshwAACuxOAfpshABACuxCAbpsggQCiuzQAgMCSu0Az0cEA0rsQME6bAsL7ElBOmzMSUsCCuxIgTpAbBAL7AA1rE1EemwNRCwNCDWEbQfDQANBCuwHy+0NA0ADQQrsAsysh80CiuzQB8MCSuwNRCxOwErsAQysRQR6bMpFDsIK7QoDQANBCuwKC+0KQ0ADQQrsUEBK7E7NBEStRAcIiUsOCQXObAoEbEYGjk5ALE4GBESsRYaOTmwPRGxFAA5ObEIAxESsBM5sSwQERKxHzQ5OTAxEzQkOwE1NCYjIgYVIzQ+ATMyFhcRFBcVIyYnBiMiJhM0NjMyFjMyNjUXFAYjIi4CIyIGFQMUFjMyNjc1IyIGWgEB75VeYFNq83bLfb7iAyn4EAx0qKPOb39fOaE0JjaVf2AnOWkrGiY1EV1OSH8gg4eIAS+tuUdUZVNAWZtYv63+GJJXER9GeboEPm6WWjkvDG6SETwMOS78bEZTRjvMXgAAAAQAWv/sA/sFzAAeACcAMgA7AM4AshgAACuyHAAAK7ErB+myEAEAK7EIBumyCBAKK7NACAwJK7QDMBwQDSuxAwTpsCYvsDkzsSIK6bA1MgGwPC+wANaxKBHpsx8oAAgrsSQM6bAoELEuASuwBDKxFBHpsBQQsDgg1hGxMwzpsDMvsTgM6bE9ASuxHwARErAMObAoEbEhJjk5sCQSsxwiCyUkFzmwMxGyCBArOTk5sTguERKzGBo1OiQXOQCxKxgRErEWGjk5sDARsRQAOTmxCAMRErATObEiJhESsTM4OTkwMRM0JDsBNTQmIyIGFSM0PgEzMhYXERQXFSMmJwYjIiYTNDYyFhQGIiYTFBYzMjY3NSMiBgE0NjIWFAYiJloBAe+VXmBTavN2y32+4gMp+BAMdKijzntDdkREdkN4XU5IfyCDh4gBUUN2RER2QwEvrblHVGVTQFmbWL+t/hiSVxEfRnm6BLAyRERkRET8JEZTRjvMXgO3MkREZEREAAAAAAQAWv/sA/sGXgAeACkAMwA+ANUAshgAACuyHAAAK7EiB+myEAEAK7EIBumyCBAKK7NACAwJK7QDJxwQDSuxAwTpsDIvtDcEAA8EK7A9L7QtBAAPBCsBsD8vsADWsR8R6bAfELErASu0NA0ADQQrsDQQsSUBK7AEMrEUEemzMBQlCCu0Og0ADQQrsDovtDANAA0EK7FAASuxHwARErAMObE0KxESsAs5sDoRtQgcIhAyLSQXObEwJRESsRgaOTkAsSIYERKxFho5ObAnEbEUADk5sQgDERKwEzmxPTcRErMqLzArJBc5MDETNCQ7ATU0JiMiBhUjND4BMzIWFxEUFxUjJicGIyImNxQWMzI2NzUjIgYSNDYzMhYUBiMiJxQWMzI2NTQmIgZaAQHvlV5gU2rzdst9vuIDKfgQDHSoo87zXU5IfyCDh4gNf19dgH1gYQ9CLi9BP2I/AS+tuUdUZVNAWZtYv63+GJJXER9GebqiRlNGO8xeA5uqe3uqeM0vQUAwLkNDAAAAAwBI/+wGhARQACkANAA8AK0AsicAACuwIjOxLQbpsBsysg8BACuwEzOxCAfpsDoytDUYJw8NK7AxM7E1BemwAzIBsD0vsADWsSoR6bAqELExASuwBDKxGBDpsDUysBgQsTYBK7EWEOmxPgErsSoAERKwDDmwMRGyCw8nOTk5sBgSsREkOTmwNhGxGyI5ObAWErEeHzk5ALEtJxESsR8kOTmwGBGzAB4qMCQXObEINRESsQsMOTmwDxGwETkwMRM0NjsBNTQmIyIGFSc0NjMyFzYXMhIdASEeATMyPwEXDgEjIicOASMiJjcUFjMyNjc1Iw4BASE1NCYjIgZI7um/X1hbc/L9xd9vg8jU7v1JCZiGiWs9SUbRcf2MQdaGsMjyXVg6iC3EaHgClgHEbWVjfwE4nqxHW2dZQhOSuYWHAv7964mLnjoipjhAoU1UsJhBTzsr0QJfAQgecXqKAAAAAAIAT/48A/UETgAcACsAigCyGgAAK7QeBAAPBCuyBAEAK7ELB+myCwQKK7NACwcJK7AlL7QmBAAPBCsBsCwvsADWsQ8R6bAPELEpASuxIg3psCIQsRUBK7AIMrEWD+mwBzKxLQErsSkPERK3BAsSGh0eJSYkFzmwIhGxIB85OQCxGiYRErIdICI5OTmxCx4RErISFRY5OTkwMRM1NAAzMhYXIy4BIyIGBxUUFjMyNjczDgIjIgABNzMHFhUUBiMnMjY1NCZPAQjkwfMG5QR3XHaAAX94W3gE5QR2ynXj/vYBWyCxC5asmwdCR0cCFRn3ASnht114q64nsK1qTmWvZgEm/mGLNhuSaXaJLyotIwAAAwBT/+wECwYAABUAGQAhAFoAshMAACuxDQfpsgUBACuxHwfptBoKEwUNK7EaBemwFi8BsCIvsBvWsQgQ6bIbCAors0AbAAkrsSMBK7EIGxESsQ8QOTkAsQoNERKxDxA5ObEWBRESsBg5MDETNTQSNjMyEhEVIR4BMzI3Fw4BIyIAEyETIwMhNS4BIyIGU33ii93x/T0LnXenaYNB2Yfn/uF/ARXDypQBzwhyZWR7AgEeogD/jv7m/v5ihpyHfWFrASME8f7R/bESen2MAAAAAAMAU//sBAsGAAAVAB0AIQBcALITAAArsQ0H6bIFAQArsRsH6bQWChMFDSuxFgXpsB8vAbAiL7AX1rEIEOmyFwgKK7NAFwAJK7EjASuxCBcRErIPECA5OTkAsQoNERKxDxA5ObEfBRESsB45MDETNTQSNjMyEhEVIR4BMzI3Fw4BIyIAEyE1LgEjIgYbASEBU33ii93x/T0LnXenaYNB2Yfn/uH5Ac8IcmVke1PDARX+6wIBHqIA/47+5v7+Yoach31hawEjAXMSen2MAdIBL/7RAAAAAwBT/+wECwYBABUAHgAmAF0AshMAACuxDQfpsgUBACuxJAfptB8KEwUNK7EfBemwGC8BsCcvsCDWsQgQ6bIgCAors0AgAAkrsSgBK7EIIBESsw8QGhskFzkAsQoNERKxDxA5ObEYBRESsBY5MDETNTQSNjMyEhEVIR4BMzI3Fw4BIyIAEzUBMwEVIycHAyE1LgEjIgZTfeKL3fH9PQudd6dpg0HZh+f+4YIBD48BEcOWlUoBzwhyZWR7AgEeogD/jv7m/v5ihpyHfWFrASMD0Q0BFP7qC5yc/aISen2MAAAEAFP/7AQLBcwAFQAeACYALwCpALITAAArsQ0H6bIFAQArsSQH6bQfChMFDSuxHwXpsB0vsC0zsRkK6bApMgGwMC+wFtaxGwzpsBsQsSABK7EIEOmyIAgKK7NAIAAJK7MsCCAIK7EnDOmwJy+xLAzpsTEBK7EbFhESsgsKHzk5ObAnEbMNEwUkJBc5sCASsiIpLjk5ObAsEbIPKi05OTmwCBKwEDkAsQoNERKxDxA5ObEZHRESsScsOTkwMRM1NBI2MzISERUhHgEzMjcXDgEjIgATNDYyFhQGIiYTITUuASMiBgE0NjIWFAYiJlN94ovd8f09C513p2mDQdmH5/7hdkN2RER2Q4MBzwhyZWR7ATVDdkREdkMCAR6iAP+O/ub+/mKGnId9YWsBIwRHMkREZERE/V4Sen2MAlYyRERkREQAAAAC/7QAAAGMBfkAAwAHACcAsgQAACuyBQEAKwGwCC+wBNaxBxHpsQkBK7EHBBESsQMBOTkAMDEDIRMjAxEzEUwBFcPKM/MF+f7R+zYEOvvGAAIAjwAAAmkF+QADAAcAKgCyAAAAK7IBAQArAbAIL7AA1rAEMrEDEemxCQErsQMAERKxBQc5OQAwMTMRMxEDEyEBj/PxwwEV/usEOvvGBMoBL/7RAAL/twAAAmYF+gAIAAwAKQCyCQAAK7IKAQArAbANL7AJ1rEMEemxDgErsQwJERKyAwIHOTk5ADAxAzUBMwEVIycHExEzEUkBD48BEcOWlRfzBNkNART+6gucnPsnBDr7xgAAAAAD/6sAAAJxBcUACAAMABUAZQCyCQAAK7IDAgArsA8zsQcK6bATMrIKAQArAbAWL7AJ1rEMEemzBQwJCCuxAAzpsAAvsQUM6bMNDAkIK7ESDOmxFwErsQkAERKxAwY5ObESDBESsQ8UOTkAsQMHERKxDRI5OTAxAzQ2MhYUBiImExEzEQM0NjIWFAYiJlVDdkREdkPk8w5DdkREdkMFTzJERGRERPrjBDr7xgVOMkREZEREAAACAGf/7ARABiwAHQArAFwAshoAACuxIQfpsCkvsQQG6QGwLC+wANaxHhHpsB4QsSQBK7EWEemxLQErsR4AERKxDQ45ObAkEbYECgYQExoLJBc5sBYSsRESOTkAsSkhERKwADmwBBGwBjkwMRM0PgEzMhcmJwcnNyYnNxYXNxcHEhEVFAIGIyIuATcUFjMyNj0BJy4BIyIGZ3HOhJJxMX7MTqx+okvusbROmv5+5YyK4n7zjW5viQEge05+iwHUled9W6l6h21yUirDMod4bWf+9/5vUqb++ZJ+4oh+qMitdBIwOKgAAAAAAgB5AAAD+AX2ABAAJgCKALIAAAArsAgzsgEBACuyBQEAK7ENCOmwHi+xFwTpsyMXHggrsRQE6QGwJy+wANaxEBHpsQImMjKwEBC0EQ0ADQQrsBEvsBAQsQkBK7EIEemzGggJCCu0Gw0ADQQrsSgBK7EQERESsAM5sAkRtAUUFx4jJBc5ALEBDRESsAM5sR4FERKxESY5OTAxMxEzFzYzIBMRIxE0JiMiBxEDNDYzMhYzMjY1FxQGIyIuAiMiBhV55Qd4wwFSBvNZZZNInX9fOaE0JjaVf2AnOWkrGiY1BDp9kf59/TUCvWdjhfz+BORullo5LwxukhE8DDkuAAAAAAMAT//sBD0GAAAPABMAHgBVALINAAArsRcH6bIFAQArsRwH6bAQLwGwHy+wANaxFBHpsBQQsRkBK7EJEemxIAErsRQAERKwEDmwGRG0BRENExIkFzmwCRKwBzkAsRAFERKwEjkwMRM1NBI2MzIAHwEUDgEjIgATIRMjAxQWMjY1NCYjIgZPfuSU2wERCwF75Zbl/u2YARXDyrOK9omNeXeMAhsMnwD/if7m6Tmg/IoBMQTj/tH9Qae9wLmkwL0AAAMAT//sBD0GAAAPABoAHgBRALINAAArsRMH6bIFAQArsRgH6bAcLwGwHy+wANaxEBHpsBAQsRUBK7EJEemxIAErsRUQERK0BQ0bHB4kFzmwCRGxBx05OQCxHAURErAbOTAxEzU0EjYzMgAfARQOASMiADcUFjI2NTQmIyIGGwEhAU9+5JTbARELAXvlluX+7fOK9omNeXeMg8MBFf7rAhsMnwD/if7m6Tmg/IoBMfWnvcC5pMC9AgMBL/7RAAAAAAMAT//sBD0GAQAPABgAIwBcALINAAArsRwH6bIFAQArsSEH6bASLwGwJC+wANaxGRHpsBkQsR4BK7EJEemxJQErsRkAERKxEBE5ObAeEbUFEhMWGA0kFzmwCRKyBxQVOTk5ALESBRESsBA5MDETNTQSNjMyAB8BFA4BIyIAEzUBMwEVIycHAxQWMjY1NCYjIgZPfuSU2wERCwF75Zbl/u2bAQ+PARHDlpVpivaJjXl3jAIbDJ8A/4n+5uk5oPyKATEDww0BFP7qC5yc/TKnvcC5pMC9AAAAAAMAT//sBD0F9gAPACUAMACIALINAAArsSkH6bIFAQArsS4H6bAdL7EWBOmzIhYdCCuxEwTpAbAxL7AA1rEmEemwJhCwJSDWEbQQDQANBCuwEC+0JQ0ADQQrsCYQsSsBK7EJEemwGSDWEbQaDQANBCuxMgErsRklERK2DRMFHSgpLiQXObEJGhESsAc5ALEdBRESsRAlOTkwMRM1NBI2MzIAHwEUDgEjIgATNDYzMhYzMjY1FxQGIyIuAiMiBhUDFBYyNjU0JiMiBk9+5JTbARELAXvlluX+7YN/XzmhNCY2lX9gJzlpKxomNSWK9omNeXeMAhsMnwD/if7m6Tmg/IoBMQPHbpZaOS8MbpIRPAw5Lv02p73AuaTAvQAABABP/+wEPQXMAA8AGAAjACwAmACyDQAAK7EcB+myBQEAK7EhB+mwFy+wKjOxEwrpsCYyAbAtL7AA1rEZEemzEBkACCuxFQzpsBkQsR4BK7EJEemzKQkeCCuxJAzpsCQvsSkM6bEuASuxGRARErESFzk5sBURshMWGzk5ObAkErINBSE5OTmwHhGyHCYrOTk5sCkSsScqOTmwCRGwBzkAsRMXERKxJCk5OTAxEzU0EjYzMgAfARQOASMiABM0NjIWFAYiJhMUFjI2NTQmIyIGATQ2MhYUBiImT37klNsBEQsBe+WW5f7tj0N2RER2Q2SK9omNeXeMAWVDdkREdkMCGwyfAP+J/ubpOaD8igExBDkyRERkRET87qe9wLmkwL0ChzJERGRERAADAEMAkwQ3BMwAAwAPABkALgCwDS+xBwvpsAAvsQEJ6bAYL7ETC+kBsBovsATWsBAysQoV6bAVMrEbASsAMDETNSEVATQ2MzIWFRQGIyImEDQ2MzIWFAYjIkMD9P18SkNESkpEQ0pKQ0RKSkRDAkbU1P7QOkxMOjlKSgMxckxMcksAAAADAE//dwQ9BLsAFQAdACUAagCyDwAAK7EgB+myBAEAK7EbB+kBsCYvsADWsRYR6bAWELEjASuxCxHpsScBK7EWABESsRMUOTmwIxG1BgQSDxkeJBc5sAsSsAc5ALEgDxESsREUOTmwGxGzCwAYJSQXObAEErEGCTk5MDETNBI2MzIXNzMHFhEUDgEjIicHIzcmExQXASYjIgYTFjMyNjU0J09+5JRqWEeRZsR75ZZdWkiRZs7zQAErLzl3jKcrM3uJOgInnwD/iSKP0Jn+wKD8ih6Tz5YBNpxiAmEWvf3xEcC5lF0AAAAAAgB3/+wD9wYAABAAFABjALILAAArsg4AACuxBQjpsgEBACuwCDOwES8BsBUvsADWsQMR6bADELEHASuwCzKxChHpsRYBK7EDABESsBE5sAcRsw4SExQkFzmwChKwDDkAsQULERKwDDmxEQERErATOTAxExEzERQzMjcRMxEjJwYjIiYTIRMjd/OrsT7z5QZrxbC1aQEVw8oBfQK9/UbOfwMJ+8Zqfs4FRv7RAAIAd//sA/cGAAAQABQAXwCyCwAAK7IOAAArsQUI6bIBAQArsAgzsBIvAbAVL7AA1rEDEemwAxCxBwErsAsysQoR6bEWASuxBwMRErMOERIUJBc5sAoRsQwTOTkAsQULERKwDDmxEgERErAROTAxExEzERQzMjcRMxEjJwYjIiYBEyEBd/OrsT7z5QZrxbC1AUfDARX+6wF9Ar39Rs5/Awn7xmp+zgQXAS/+0QACAHf/7AP3BgEAEAAZAGoAsgsAACuyDgAAK7EFCOmyAQEAK7AIM7ATLwGwGi+wANaxAxHpsAMQsQcBK7ALMrEKEemxGwErsQMAERKxERI5ObAHEbQOExQXGSQXObAKErIMFRY5OTkAsQULERKwDDmxEwERErAROTAxExEzERQzMjcRMxEjJwYjIiYTNQEzARUjJwd386uxPvPlBmvFsLVsAQ+PARHDlpUBfQK9/UbOfwMJ+8Zqfs4EJg0BFP7qC5ycAAAAAwB3/+wD9wXMABAAGQAiAJ4AsgsAACuyDgAAK7EFCOmyAQEAK7AIM7AYL7AgM7EUCumwHDIBsCMvsADWsQMR6bARINYRsRYM6bADELEHASuwCzKxChHpsAoQsB8g1hGxGgzpsBovsR8M6bEkASuxAxERErETGDk5sBYRsRQXOTmwGhKxDgU5ObAHEbEcITk5sB8SsgwdIDk5OQCxBQsRErAMObEUGBESsRofOTkwMRMRMxEUMzI3ETMRIycGIyImEzQ2MhYUBiImJTQ2MhYUBiImd/OrsT7z5QZrxbC1YEN2RER2QwHJQ3ZERHZDAX0Cvf1Gzn8DCfvGan7OBJwyRERkREQxMkREZEREAAIADP5LA9YGAAAPABMAYQCyAAEAK7ADM7AHL7ELA+mwES8BsBQvsADWsQET6bABELEDASuxBBPpsRUBK7EBABESsgcJCjk5ObADEbMPEBETJBc5sAQSsBI5ALELBxESsAk5sAARsAI5sBESsBA5MDETIRsBIQECIyInNRcyNj8BAxMhAQwBBuXcAQP+UmPtNUAuXF0bIwLDARX+6wQ6/SIC3vsi/u8SvANDT10EzAEv/tEAAAIAgv5gBDcGAAAPABoAVQCyDAAAK7ESB+myBQEAK7EYCOmwAC+wAS8BsBsvsADWsQ8R6bECEDIysA8QsRUBK7EJEemxHAErsRUPERKxBQw5OQCxEgwRErAOObEFGBESsAM5MDETETMRNjMyEhEVFAIjIicZARYzMjY1NCYjIgeC82qwxePjwrJrQpZ0g4N2lUH+YAeg/dd3/tr++hD3/tF1/f8CzH67vqa6ewADAAz+SwPWBcwADwAYACEAoACyAAEAK7ADM7AHL7ELA+mwFy+wHzOxEwrpsBsyAbAiL7AQ1rEVDOmzARUQCCuxABPpsAAvsQET6bAVELEDASuxBBPpsBkg1hGxHgzpsSMBK7EQABESsQkKOTmwARGyBxIXOTk5sBUSsg8TFjk5ObAZEbACObADErEbIDk5sB4RsRwfOTkAsQsHERKwCTmwABGwAjmxExcRErEZHjk5MDETIRsBIQECIyInNRcyNj8BAzQ2MhYUBiImJTQ2MhYUBiImDAEG5dwBA/5SY+01QC5cXRsj6UN2RER2QwHJQ3ZERHZDBDr9IgLe+yL+7xK8A0NPXQVRMkREZEREMTJERGRERAACAGT/7ActBcQAFwAjAIQAshIAACuxDwPpshQAACuxGwfpsgcCACuxCgPpsgUCACuxIAfptAsOFAUNK7ELCOkBsCQvsADWsRgR6bAYELEdASuxDwzpsAoysg8dCiuzQA8JCSuwEDKzQA8NCSuxJQErsR0YERKxFAU5ObAPEbASOQCxDxsRErAdObEgChESsB45MDETETQSJDMyFyEVIREhFSERIRUhBiMiJAI3FBYzMjcRJiMiBgdkkQELqHunA1z9TAJW/aoCu/ydp3mn/veU8bKhY2hyW6GvAQI2ATqsARKWFMz+bsj+QMoUkwENtMHRDQQ4Ds+8AAMAW//sBvIETwAeACoAMgCAALIcAAArsBgzsSIH6bARMrIEAQArsAkzsSgH6bAwMrQrDhwEDSuxKwXpAbAzL7AA1rEfEemwHxCxLAErsQwQ6bE0ASuxLB8RErcEBhEYHA4lKyQXObAMEbEUFTk5ALEiHBESsRUaOTmwDhGwFDmwKxKxHyU5ObEEKBESsAY5MDETNTQAMzIXPgEXMhIdASEeATMyNjcXDgEjIicGIyIANxQWMzI2NTQmIyIGBSE1NCYjIgZbAQ/g+YZBt23W7v1WC5F1WY9HT0fNePeMhvbj/vLyhnl3hod4dYgDAAG1cWNVeAIbDPgBL7FUXgH+/eyIi54qMp4/Qa6uAS35qrq5wKa+ukgZb3qJAAAAAwAHAAAE1gcCAAgAEQAaAHoAsgcAACuyAAIAK7ADM7AQL7AYM7EMCumwFDIBsBsvsAfWsQYM6bMOBgcIK7EJDOmwCS+xDgzpsxIGBwgrsRcM6bEcASuxBwkRErIBDA85OTmxEg4RErACObEXBhESsgMUGTk5OQCxAAcRErACObEMEBESsRIXOTkwMRMhCQEhAREjEQM0NjIWFAYiJiU0NjIWFAYiJgcBGQFPAU8BGP4Y/uBDdkREdkMByUN2RER2QwWw/U4Csvxo/egCGAR0MkREZEREMTJERGRERAAAAAABAJQE4ANDBgEACAAhALAAL7AFM7QCCwAWBCsBsAkvsQoBKwCxAgARErAHOTAxEzUBMwEVIycHlAEPjwERw5aVBOANART+6gucnAAAAQB6BNsDVwX1ABUAPwCwDS+xBgTpsxIGDQgrsQME6QGwFi+wANa0FQ0ADQQrsBUQsQkBK7QKDQANBCuxFwErsQkVERKxAw05OQAwMRM0NjMyFjMyNjUXFAYjIi4CIyIGFXp/XzmhNCY2lX9gJzlpKxomNQTjbpZaOS8MbpIRPAw5LgAAAQBHAgkCVALNAAMAABM1IRVHAg0CCcTEAAAAAAEARwIJAlQCzQADAAATNSEVRwINAgnExAAAAAABAEcCCQJUAs0AAwAAEzUhFUcCDQIJxMQAAAAAAQCeAm0EmAMxAAMAFwCwAC+xAQfpsQEH6QGwBC+xBQErADAxEzUhFZ4D+gJtxMQAAQCCAm0F0AMxAAMAFwCwAC+xAQfpsQEH6QGwBC+xBQErADAxEzUhFYIFTgJtxMQAAQBjBCABlgYaAAgAJQCwAC+0BAsACQQrAbAJL7AA1rEIDemxCgErsQgAERKwBDkAMDETNT4BNxcGBxVjAWdPfFsDBCCKYNE/TYWQmAAAAAABADMEAAFlBgAACAAlALAIL7QDCwAIBCsBsAkvsALWsQUN6bEKASuxBQIRErAIOQAwMRM2NzUzFRQGBzNaA9VpTQRNg5KeimfRPgAAAQAy/tYBZADKAAgAJQCwCC+0AwsACQQrAbAJL7AC1rEFDemxCgErsQUCERKwCDkAMDEXNjc1MxUOAQcyVQPaAWZQ3H+Uk4Vd0EIAAAIAbAQgAu8GGgAIABEAQgCwAC+wCTO0BAsACQQrsA0yAbASL7AA1rEIDemwCBCxCQErsREN6bETASuxCAARErAEObAJEbAFObARErANOQAwMRM1PgE3FwYHFTM1PgE3FwYHFWwBZ098WwN7AWdPfFsDBCCKYNE/TYWQmIpg0T9NhZCYAAIAQAQAAsAGAAAIABEAQgCwCC+wETO0AwsACAQrsAwyAbASL7AC1rEFDemwBRCxCwErsQ4N6bETASuxBQIRErAIObALEbAJObAOErAROQAwMRM2NzUzFRQGBzc2NzUzFRQGB0BaA9VpTdJaA9VpTQRNg5KeimfRPk2Dkp6KZ9E+AAAAAAIAMv7CAqoA/wAJABIAQgCwCS+wEjO0AwsACAQrsA0yAbATL7AC1rEFDemwBRCxDAErsQ8N6bEUASuxBQIRErAJObAMEbAKObAPErASOQAwMRc2NzUzFQYHBgc3Njc1MxUUBgcyVQPaATcxSsNYBNpmUfCJncm6bHJkQU6Olsu2Y91HAAEAiAIGAkQD2wANAC4AsAsvtAQLAAkEK7QECwAJBCsBsA4vsADWtAgVAAoEK7QIFQAKBCuxDwErADAxEzU0NjMyFh0BFAYjIiaIeWRneHdnY3kC1i1feXliJV53cwAAAAMAiv/1BSgBAAAKABUAIABFALIJAAArsRQfMzOxAwvpsQ4ZMjKyCQAAK7EDC+kBsCEvsAHWsQYV6bAGELEMASuxERXpsBEQsRcBK7EcFemxIgErADAxNjQ2MzIWFRQGIyIkNDYzMhYVFAYjIiQ0NjMyFhUUBiMiikpDREpKREEBfkpDREpKREEBbUpDREpKREE/dE1NOjlLSnRNTTo5S0p0TU06OUsAAAEAbACKAjMDqQAGACEAAbAHL7AA1rQFFQAJBCuwAzKxCAErsQUAERKwBDkAMDETNQEzAxMjbAEgp/f3pwIQEwGG/nD+cQAAAAEAVACKAhsDqQAGACEAAbAHL7AA1rACMrQFFQAJBCuxCAErsQUAERKwATkAMDE3EwMzARUBVPf3pwEg/uCKAY8BkP56E/56AAEAXv/tBDAFwwAjAJMAsiAAACuxGwjpsgkCACuxDgPptAABIAkNK7AVM7EABOmwFzK0BQQgCQ0rsBMzsQUE6bARMgGwJC+wI9axAgYyMrEYDOmxERQyMrIYIwors0AYFwkrsBIysiMYCiuzQCMACSuwBDKxJQErsRgjERKxByI5OQCxGyARErAeObAAEbAdObEOBRESsAw5sAkRsAs5MDETNTM1IzUzEgAzMhcHJiMiBgchFSEVIRUhHgEzMjcXBiMgAANerKytDQEs/WqFHGZll6IJAWP+nAFk/pwGo5huXxx4gP8A/toIAg+NgI0A/wEbH80irKSNgI2urCHMHQEgAQIAAgBtA5QEVwWwAAcAFACRALIJAgArsQEMMzO0CAsACAQrsgUOETIyMrIJAgArtAgLAAgEK7IJAgArtAAEAA8EK7ADMgGwFS+wBta0BQ0ADQQrsgUGCiuzQAUDCSuyBgUKK7NABgAJK7AFELEIASu0FA0ADQQrsBQQsQ8BK7QODQANBCuxFgErsQ8UERKxCgw5OQCxAAgRErILEBM5OTkwMRM1IRUjESMRAREzGwEzESMRAyMDEW0BjIp1AUmJgYWFb3w+fAVRX1/+RQG7/kMCHP6DAX395AF1/osBdP6MAAABAAAAAAQ4BDgAAwA1ALIAAAArtAELAAcEK7IAAAArtAELAAcEKwGwBC+wANa0AxUABwQrtAMVAAcEK7EFASsAMDExESERBDgEOPvIAAAAAAIAGAAABBcGFQAXABsAegCyFgAAK7AYM7IBAQArsREZMzOxAAXpsBMysA0vsQcJ6QGwHC+wFtawAjKxFRHpsBAyshUWCiuzQBUTCSuyFhUKK7NAFgAJK7AVELEYASuxGxHpsR0BK7EYFRESsQ0HOTmwGxGxCwo5OQCxDQERErALObAHEbAKOTAxEzUzNT4CMzIWFwcmIyIGHQEzFSMRIxEBETMRGKUBasKIUJNPJYpyb2TV1fMCZ/MDhrRKf7ZcIhrJMGFhRLT8egOG/HoEOvvGAAAAAQAtAAAELAYVABYAbgCyFQAAK7AJM7IBAQArsBAzsQAF6bASMrANL7EGCOkBsBcvsBXWsAIysRQR6bAPMrIUFQors0AUEgkrshUUCiuzQBUACSuwFBCxCgErsQkR6bEYASuxChQRErAGOQCxDQERErALObAGEbAIOTAxEzUzNT4BMzIFESMRJiMiHQEzFSMRIxEtpQHXxHoBRPNmSsTc3PMDhrRht8Mw+hsFPw64W7T8egOGAAAAAAIALQAABpMGFQAoACwApQCyJwAAK7EiKTMzsgEBACuyDh4qMzMzsQAF6bEgJDIysAsvsBozsQYI6bAUMgGwLS+wJ9awAjKxJhHpsA0ysicmCiuzQCcACSuwJhCxIwErsA8ysSIR6bAdMrIiIwors0AiIAkrsCIQsSkBK7EsEemxLgErsSMmERKxBgg5ObEpIhESsRoUOTmwLBGxGBc5OQCxCwERErEJGDk5sAYRsQgXOTkwMRM1MzU0NjMyFwcmIyIdASE1PgIzMhYXByYjIgYdATMVIxEjESERIxEBETMRLaXItEBIBig1rgF0AWrCiFCTTyaIc29k1dXz/ozzBM7zA4a0Y7TEEr4Is2BKf7ZcIhrJMGFhRLT8egOG/HoDhvx6BDr7xgAAAQAtAAAGkwYVACcAmQCyJgAAK7EWITMzsgEBACuxDh0zM7EABemxHyMyMrALL7AaM7EGCOmwEzIBsCgvsCbWsAIysSUR6bANMrImJQors0AmAAkrsCUQsSIBK7APMrEhEemwHDKyISIKK7NAIR8JK7AhELEXASuxFhHpsSkBK7EiJRESsQYIOTmxFyERErATOQCxCwERErEJGDk5sAYRsQgVOTkwMRM1MzU0NjMyFwcmIyIdASE1PgEzMgURIxEmIyIdATMVIxEjESERIxEtpci0QEgGKDWuAXQB18R6AUTzZkrE3Nzz/ozzA4a0Y7TEEr4Is2Bht8Mw+hsFPw64W7T8egOG/HoDhgAAAAEAAAACIxKOYEf7Xw889QAfCAAAAAAAxPARLgAAAADaq65+/6v+JgdXB5QAAAAIAAIAAAAAAAAAAQAACHP9rQAAB7T/q/+pB1cAAQAAAAAAAAAAAAAAAAAAAOoC7ABEAAAAAAH+AAAAAAAAAf4AAAIlAI8CmABlBOIAYASMAGQF4ABjBR0AVgFaAFICygCAAtIAKAOJABsEdQBEAcIAHAKgAEcCPACHAyoAAgSMAGkEjACoBIwAUQSMAE8EjAA0BIwAgQSMAHUEjABFBIwAaASMAF0CHwCCAecALgQRAD8EegCRBCoAgAPkADwHKABbBVMAEgUMAJQFOQBmBToAlASGAJQEZQCUBXIAagWvAJQCQgCjBHEALQULAJQEVACUBwEAlAWuAJQFhgBmBR0AlAWGAGAE/gCUBNQASgTbAC0FNwB9BS0AEgcKADAFEAApBOAABwTRAFACMQCEA1gAFAIxAAwDawA1A5wAAwKUADEEVABaBIEAfAQwAE8EhABPBEsAUwLWAC0EiQBSBHEAeQILAH0CAf+1BC0AfQILAIwG9gB8BHMAeQSOAE8EgQB8BIsATwLQAHwEIQBLAqkACARyAHcD9QAWBfIAIQQGAB8D5QAMBAYAUgKvADgCAgCuAq8AGwVRAHUB/gAAAh4AhgR9AGQEtQBeBZ0AXQRAAAsB/ACIBPgAWgOFAF0GRABXA5EAjQPiAFcEbQB/AqAARwZEAFcD2wCbAwoAfwRKAF8C9gA8AvYANwKbAHAEuwCSA+0ARQJCAI4CEABtAvYAgAOnAHcD4gBdBdAAWQYrAFAGVwBnA+QAQgVTABIFUwASBVMAEgVTABIFUwASBVMAEgeF//YFOQBmBIYAlASGAJQEhgCUBIYAlAJC/8gCQgCjAkL/ywJC/78FWP/3Ba4AlAWGAGYFhgBmBYYAZgWGAGYFhgBmBEQATQWEAGkFNwB9BTcAfQU3AH0FNwB9BOAABwTKAJQE5wCIBFQAWgRUAFoEVABaBFQAWgRUAFoEVABaBsEASAQwAE8ESwBTBEsAUwRLAFMESwBTAhr/tAIaAI8CGv+3Ahr/qwSnAGcEcwB5BI4ATwSOAE8EjgBPBI4ATwSOAE8EkQBDBIgATwRyAHcEcgB3BHIAdwRyAHcD5QAMBJcAggPlAAwHtABkBzoAWwTgAAcD5gCUA9gAegPKAAAHlAAAA8oAAAeUAAAChgAAAeUAAAFDAAABQwAAAPIAAAGEAAAAawAAAqAARwKgAEcCoABHBSkAngYwAIIBwABjAbwAMwHOADIDFABsAxsAQAMIADICywCIBaYAigGEAAACcgBsAmkAVAHlAAAEjABeBQkAbQQ4AAAEqAAYBLwALQcjAC0ALQAAAAAALAAsACwALAAsAGwApAGOAhwCwgNaA4ADrgPiBCIEZASMBKoE1ATsBToFZAXEBkgGkgcQB3QHmAgeCIYIwAkCCR4JQAlcCc4KlgrICywLigvIDAQMOgykDNwM+g02DWwNkg3gDhoObg6yDxYPcg/kEBQQUBCEEOwRIBFQEX4RqhHAEfISEBIqEkgSxhMiE3wT3BQ2FIIU/hU+FXoVxhX8FhgWfhbCFxAXbBfMGAAYcBjEGQgZOhmgGdIaGhpIGogaphrmGzwbPBt8G+gcYhziHUYdbB4QHk4fBB96H5ofwh/gIKYgviEKIVYhtCIuIk4imCLMIvIjKiNeI6gjyiRSJPIlyiZEJn4muib8J3In4ChYKL4pSimSKdYqJiqcKsYq8CsiK3wr2ixULLItEC10LgYumC66LzIvei/EMBowkjDOMRYxmjIoMrgzUDQWNNY1mjZKNtI3OjekOBQ4tjjeOQg5OjmUOgg6iDroO0g7tDxCPNY9GD2MPeI+OD6aPyA/ej/QQFpA1kFkQdRB+kI8QjxCPEI8QjxCPEI8QjxCPEI8QjxCPEJKQlhCZkJ+QpZCvkLkQwpDTEOOQ9BEAERURFREeEScRJxFHkWORbZGIEZ8RxBHlgABAAAA6wBDAAUAAAAAAAIAAQACABYAAAEAAWYAAAAAAAAAFAD2AAMAAQQJAAAAXgAAAAMAAQQJAAEAGgBeAAMAAQQJAAIADgB4AAMAAQQJAAMAGgCGAAMAAQQJAAQAKgCgAAMAAQQJAAUAJgDKAAMAAQQJAAYAGgDwAAMAAQQJAAcAQAEKAAMAAQQJAAkADAFKAAMAAQQJAAsAFAFWAAMAAQQJAAwAJgFqAAMAAQQJAA0AXAGQAAMAAQQJAA4AVAHsAAMAAQQJABAADAJAAAMAAQQJABEADAJMAAMAAQQJAMgAFgJYAAMAAQQJAMkAMAJuAAMAAQQJAMoADgKeAAMAAQQJAMsABgKsAAMAAQQJ2QMAGgKyAEMAbwBwAHkAcgBpAGcAaAB0ACAAMgAwADEAMQAgAEcAbwBvAGcAbABlACAASQBuAGMALgAgAEEAbABsACAAUgBpAGcAaAB0AHMAIABSAGUAcwBlAHIAdgBlAGQALgBSAG8AYgBvAHQAbwAgAE0AZQBkAGkAdQBtAFIAZQBnAHUAbABhAHIAUgBvAGIAbwB0AG8AIABNAGUAZABpAHUAbQBSAG8AYgBvAHQAbwAgAE0AZQBkAGkAdQBtACAAUgBlAGcAdQBsAGEAcgBWAGUAcgBzAGkAbwBuACAAMgAuADEAMwA3ADsAIAAyADAAMQA3AFIAbwBiAG8AdABvAC0ATQBlAGQAaQB1AG0AUgBvAGIAbwB0AG8AIABpAHMAIABhACAAdAByAGEAZABlAG0AYQByAGsAIABvAGYAIABHAG8AbwBnAGwAZQAuAEcAbwBvAGcAbABlAEcAbwBvAGcAbABlAC4AYwBvAG0AQwBoAHIAaQBzAHQAaQBhAG4AIABSAG8AYgBlAHIAdABzAG8AbgBMAGkAYwBlAG4AcwBlAGQAIAB1AG4AZABlAHIAIAB0AGgAZQAgAEEAcABhAGMAaABlACAATABpAGMAZQBuAHMAZQAsACAAVgBlAHIAcwBpAG8AbgAgADIALgAwAGgAdAB0AHAAOgAvAC8AdwB3AHcALgBhAHAAYQBjAGgAZQAuAG8AcgBnAC8AbABpAGMAZQBuAHMAZQBzAC8ATABJAEMARQBOAFMARQAtADIALgAwAFIAbwBiAG8AdABvAE0AZQBkAGkAdQBtAFcAZQBiAGYAbwBuAHQAIAAxAC4AMABUAGgAdQAgAEEAcAByACAAIAAyACAAMQA1ADoAMAAwADoAMQA0ACAAMgAwADIAMABkAGUAZgBhAHUAbAB0AGwAZQBvAEYAbwBuAHQAIABTAHEAdQBpAHIAcgBlAGwAAAACAAAAAAAA/XYAZAAAAAAAAAAAAAAAAAAAAAAAAAAAAOsAAAECAQMBBAADAAQABQAGAAcACAAJAAoACwAMAA0ADgAPABAAEQASABMAFAAVABYAFwAYABkAGgAbABwAHQAeAB8AIAAhACIAIwAkACUAJgAnACgAKQAqACsALAAtAC4ALwAwADEAMgAzADQANQA2ADcAOAA5ADoAOwA8AD0APgA/AEAAQQBCAEMARABFAEYARwBIAEkASgBLAEwATQBOAE8AUABRAFIAUwBUAFUAVgBXAFgAWQBaAFsAXABdAF4AXwBgAGEBBQCjAIQAhQC9AJYA6ACGAI4AiwCdAKkApAEGAIoA2gCDAJMBBwEIAI0AlwCIAMMA3gEJAJ4AqgD1APQA9gCiAK0AyQDHAK4AYgBjAJAAZADLAGUAyADKAM8AzADNAM4A6QBmANMA0ADRAK8AZwDwAJEA1gDUANUAaADrAO0AiQBqAGkAawBtAGwAbgCgAG8AcQBwAHIAcwB1AHQAdgB3AOoAeAB6AHkAewB9AHwAuAChAH8AfgCAAIEA7ADuALoAsACxALsA2ADZAQoBCwEMAQ0BDgEPARABEQESARMBFAEVARYBFwCyALMAtgC3AMQAtAC1AMUAhwCrARgAvgC/ARkBGgCMARsBHAEdAR4BHwZnbHlwaDEHdW5pMDAwRAd1bmkwMDAyB3VuaTAwQTAHdW5pMDBBRAd1bmkwMEIyB3VuaTAwQjMHdW5pMDBCOQd1bmkyMDAwB3VuaTIwMDEHdW5pMjAwMgd1bmkyMDAzB3VuaTIwMDQHdW5pMjAwNQd1bmkyMDA2B3VuaTIwMDcHdW5pMjAwOAd1bmkyMDA5B3VuaTIwMEEHdW5pMjAxMAd1bmkyMDExCmZpZ3VyZWRhc2gHdW5pMjAyRgd1bmkyMDVGBEV1cm8HdW5pMjVGQwd1bmlGQjAxB3VuaUZCMDIHdW5pRkIwMwd1bmlGQjA0ALgB/4WwAY0AS7AIUFixAQGOWbFGBitYIbAQWUuwFFJYIbCAWR2wBitcWACwAyBFsAMrRLAIIEWyA9gCK7ADK0SwByBFsgh0AiuwAytEsAYgRbIHQgIrsAMrRLAFIEWyBjgCK7ADK0SwBCBFsgUaAiuwAytEsAkgRbIDwwIrsAMrRLAKIEWyCSMCK7ADK0SwCyBFsgoYAiuwAytEAbAMIEWwAytEsBEgRbIMdgIrsQNGditEsBAgRbIRRQIrsQNGditEsA8gRbIQLQIrsQNGditEsA4gRbIPJQIrsQNGditEsA0gRboADgGOAAIrsQNGditEsBIgRboADH//AAIrsQNGditEsBMgRbIShQIrsQNGditEsBQgRbITPAIrsQNGditEsBUgRbIUNAIrsQNGditEWbAUKwAAAA==) format('truetype');
}
@font-face
{
    font-family: RobotoReg; font-style: normal; font-weight: normal;
    src: url(data:font/truetype;charset=utf-8;base64,AAEAAAASAQAABAAgRkZUTXWJBW8AAAEsAAAAHEdERUYCQwF0AAABSAAAADxHUE9TAt4KrgAAAYQAABNOR1NVQr7PqY4AABTUAAACHE9TLzKXdaz0AAAW8AAAAGBjbWFwA4OKAAAAF1AAAAHqY3Z0IBJ+DDAAABk8AAAAOmZwZ21TtC+nAAAZeAAAAmVnYXNwAAAAEAAAG+AAAAAIZ2x5Zo1wRBUAABvoAACPKGhlYWQF4i1nAACrEAAAADZoaGVhD4gF7wAAq0gAAAAkaG10eK03T9QAAKtsAAADqmxvY2FEuGc+AACvGAAAAdhtYXhwAggBrwAAsPAAAAAgbmFtZSzcg2kAALEQAAADanBvc3QxqhcIAAC0fAAAAudwcmVwrlzS+AAAt2QAAAD7AAAAAQAAAADV7UW4AAAAAMTwES4AAAAA2quuiAABAAIADgAAAB4AAAAmAAIAAgABAOYAAQDnAOoAAgAEAAAAAgAAAAEAAgAAAAwAAAAQAAEAAAABAAEAewABAAAACgBcAHYABERGTFQAGmN5cmwAKGdyZWsANmxhdG4ARAAEAAAAAP//AAIAAAABAAQAAAAA//8AAgAAAAEABAAAAAD//wACAAAAAQAEAAAAAP//AAIAAAABAAJjcHNwAA5rZXJuABQAAAABAAAAAAABAAEAAgAGAA4AAQAAAAEAEgACAAAAAgBaBI4AAQAKAAUAJABIAAIACwAIAAgAAAAKAAoAAQAUAB0AAgAlAD4ADABmAGYAJgBoAGgAJwCDAJkAKACbAKEAPwDDAMMARgDFAMUARwDkAOQASAABA6QABAAAAEYAlgCcAJwAogC4AL4AzADaAOAA6gGsAbIA2gG4AcIB3AHyAhQCJgI4AnICeAKSApgCkgLqApICkgKSAxgDJgNAA0YDQANcAL4AvgC+AL4AvgC+AMwA4ADgAOAA4ADaANoA2gDaANoA2gI4ApICkgKSApICkgKSApICkgKSApIDQANAAjgAnAN2AJwAnAABADj/2AABAFsACwAFADoAFAA7ABIAPQAWAKAAFgDFABYAAQAT/yAAAwAj/8MAWP/vAFv/3wADAA3/5gBB//QAYf/vAAEAif/fAAIASv/uAFv/6gAwABD/FgAS/xYAJf9WAC7++AA4ABQARf/eAEf/6wBI/+sASf/rAEv/6wBT/+sAVf/rAFb/5gBZ/+oAWv/oAF3/6ACD/1YAhP9WAIX/VgCG/1YAh/9WAIj/VgCj/94ApP/eAKX/3gCm/94Ap//eAKj/3gCq/+sAq//rAKz/6wCt/+sArv/rALX/6wC2/+sAt//rALj/6wC5/+sAvP/qAL3/6gC+/+oAv//qAMD/6ADC/+gAxP/rANr/FgDd/xYA3/8WAAEAW//BAAEAW/+kAAIAWAAOAIn/nwAGADj/1QA6/+QAO//sAD3/3QCg/90Axf/dAAUAOP+wADr/7QA9/9AAoP/QAMX/0AAIAAT/2ABW/7UAW//HAG7+uAB+/ygAif9NAKn/jgC7/6EABAANABQAQQARAFb/4gBhABMABAANAA8AQQAMAFb/6wBhAA4ADgAK/+IADQAUAA7/zwBBABIASv/qAFb/2ABY/+oAYQATAG7/rgB+/80Aif+gAKn/wQC7/8AA3v/TAAEAW//lAAYALv/uADn/7gCc/+4Anf/uAJ7/7gCf/+4AAQDZ/7AAFAAGABAACwAQAA0AFABBABIAR//oAEj/6ABJ/+gAS//oAFX/6ABhABMAqv/oAKv/6ACs/+gArf/oAK7/6ADE/+gA2AAQANkAEADbABAA3AAQAAsAR//sAEj/7ABJ/+wAS//sAFX/7ACq/+wAq//sAKz/7ACt/+wArv/sAMT/7AADAEoADwBYADIAWwARAAYAU//sALX/7AC2/+wAt//sALj/7AC5/+wAAQBKAA0ABQAQ/4QAEv+EANr/hADd/4QA3/+EAAYALv/sADn/7ACc/+wAnf/sAJ7/7ACf/+wACwBMACAATwAgAFAAIABT/4AAV/+QAFsACwC1/4AAtv+AALf/gAC4/4AAuf+AAAEARgAEAAYACwAMABMAJQAnACgAKQAqAC8AMAAzADQANQA2ADgAOgA7AD0APgA/AEkASgBMAE8AUQBSAFMAVgBYAFoAWwBdAF8AgwCEAIUAhgCHAIgAigCLAIwAjQCOAJMAlQCWAJcAmACZAKAAqwCsAK0ArgC0ALUAtgC3ALgAuQDAAMIAxQDYANkA2wDcAAINqAAEAAALDAxaACYAJQAAAAAAAAAAAAAAAAASAAAAAAAAAAD/4//kAAAAAAAAAAAAEQAAAAAAAAAAAAAAAAAAABEAAAARAAAAAAAAAAD/5P/lAAAAAAAAAAAAAAAAAAAAAAAA/+sAAAAAAAAAAP/l/9X/7QAAAAAAAP/qAAD/6QAAAAAAAAAAAAD/4f+aAAD/9f/qAAAAAAAAAAAAAAAAAAAAAAAA//UAAP/0//UAAAAA//X/zv/v/3//ogAAAAAADAAAAAD/8QAA/4gAAP+7/8T/xwARAAAAEgAA/6kAAAAA/8n/jwAAAAD/3QAAAAAAAAAAAAAAAAAAAAAAAP/xAAAAAAAAAAAAAP/wAAAAAAAAAAD/eP/rAAAAAAAAAAAAAP/wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP+YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/tAAAAAP/t/+8AAAAAAAD/5gAAABQAAAAAAAAAAAAAAAAAAAAAAAAAAAAA//AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/7QAAAAAAAAAAAAAAAAAAAAAAAP/xAAAAAAAAAAAAAAAAAAAAAAAAAAD/vQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA//UAAAAAAAAAAAAA//EAAAAAAAAAAP/j//EAAAAAAAAAAAAA//IAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/8wAAAAAAAAAAAAAAAAAAAAAAAAAA//IAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA//MAAAAA//EAAAAA//EAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADwAAAAAAAAAAAAD/lf/XAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/+oAAAAAAAAAAAAAAAD/6wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/m/+H/6f/l/+kAAAAA/+f/2AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/AAAD/owAAAAAAAAAA/7//4//Y/7//2f+i/7f/y//s/6AAEQAS/6v/xv/i//AADQAAAAAAAP/pABEAAP/zAAD/LQAA/+8AEgAA/8wAAAAAAAD/oP/zAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/q/+4AAAAAAAD/7AAAAAAAAAAAAAAAAAAAAAAAAP+d/+T/k/+d/6H/sf+P/7n/uAAAABAAEP+v/4z/xP/wAAAAAAAAAAD/swAPAAD/8f/L/yb/fv/tABD/vP8YAAD/fAAA/xD/8QAAAAAAAAAAAAAAAAAAAAD/8gAAAAAAAAAAAAAAAAAAAAAAAP/sAAAAAAAAAAD/v//AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/YAAD/8AAAAAD/8AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/r/+YAAP/r/+0ADQAA/+z/5QAAAAAAAAANAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/+b/5wAA/+v/6wAAAAD/5//hAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABEAAAARAAAADgAA/9IAAP/RAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/jAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/sAAAAAP/sAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/+0AAAAA/+wAAAAA/9gAAAASAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAD/hQAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/8wAAAAD/8wAA/3b/9QAAAA8AAAAAAAD/xgAAAAAAAP/hAAD/5gAAAAAAAAAAAAD/yf68/9kAAAAAAAAAAAAAAAAAAP84AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA//UAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/vwAAAAD/1AATAAD/8v97/8r+7f8RABMAAAAAAAAAAP/aAAD+sAAA/3H/P/87AAAAAAAAAAD/UQAAAAAAAAAAAAAAAP+RAAD/xQAA/+z/wwAA/4j/zgAAAAAAAAAAAAAAAP+wAAAAAAAAAAAAAP+VAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/sAAAAAP/sAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/2AAAAAAAAAAAAAAAAAAAAAAAAAAA/+EAAAAA/+H/7f/V/9//5wAAAAAADgAA/8sAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/hQAAAAAAAAAA/8QAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/l/8kAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/oAAAAAAAAAAD/8wAAAAAAAP/U//MAAP/S/+T/tf/S/9n/9QAAAAAAAP+0AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/x8AAAAAAAAAAP/bAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/6wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/90AAAAAAAAAAAAAAAAAAAAAAAAAAP95//UAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/9kAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/vX/rQAAAAAAAAAA//AAAAAA/8D/yQAAAAAAAP/1AAAAAAAA/8gAAAAA/+cAAP/rAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/VgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/RP+9/zP/RP9L/z7/LAAA/3IAAAAHAAcAAP8n/4b/0QAAAAAAAAAA/2oABQAAAAD/kv56/w8AAAAHAAD+YgAA/wwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA0AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/7wAAAAAAAAAAAAAAAAAAAAAAAP/sAAAAAAAAAAD/tP+7AAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/VAAD/vf/p/5r/vQAA/6X/kQAAAAAAAAASABIAAP/SAAAAAAAAAAAAAAAAAAAAAAAAAAD/yv5t/7sAAAAAAAD/iQAA/+kAAAAAAAAAAgA3AAYABgAZAAsACwAZABAAEAAhABIAEgAhACUAJQACACYAJgAcACcAJwATACgAKAABACkAKQAFAC4ALgAKAC8ALwALADAAMAAYADMAMwABADQANAAWADgAOAAOADkAOQAKADoAOgAdADsAOwAbADwAPAASAD0APQAMAD4APgARAEUARQAGAEYARgAHAEcARwAXAEkASQAIAEwATAAEAFEAUgAEAFMAUwADAFQAVAAHAFYAVgAVAFoAWgAJAFwAXAAUAF0AXQAJAF4AXgAQAIMAiAACAIoAigATAIsAjgAFAJMAkwABAJUAmQABAJwAnwAKAKAAoAAMAKMAqAAGAKoAqgAXAKsArgAIALQAtAAEALUAuQADAMAAwAAJAMEAwQAHAMIAwgAJAMUAxQAMANgA2QAZANoA2gAhANsA3AAZAN0A3QAhAN8A3wAhAAIANwAGAAYAFAALAAsAFAAQABAAGgARABEAHwASABIAGgAlACUABgAnACcAAgArACsAAgAuAC4AIwAzADMAAgA1ADUAAgA3ADcAEAA4ADgACwA5ADkACgA6ADoAHQA7ADsAFgA8ADwAEQA9AD0ADAA+AD4AEwBFAEUABwBHAEkAAQBLAEsAAQBRAFIAAwBTAFMABABUAFQAAwBVAFUAAQBXAFcADgBZAFkABQBaAFoACQBcAFwAFQBdAF0ACQBeAF4ADwBwAHAAHwCDAIgABgCKAIoAAgCVAJkAAgCbAJsAAgCcAJ8ACgCgAKAADACjAKgABwCqAK4AAQC0ALQAAwC1ALkABAC8AL8ABQDAAMAACQDCAMIACQDDAMMAAgDEAMQAAQDFAMUADADWANcAHwDYANkAFADaANoAGgDbANwAFADdAN0AGgDfAN8AGgACABgABgAGAAAACwALAAEAEAAQAAIAEgASAAMAJQApAAQALAA0AAkAOAA+ABIARQBHABkASQBJABwATABMAB0AUQBUAB4AVgBWACIAWgBaACMAXABeACQAgwCIACcAigCZAC0AnACgAD0AowCoAEIAqgCuAEgAtAC5AE0AwADCAFMAxQDFAFYA2ADdAFcA3wDfAF0AAAABAAAACgCeAOAABERGTFQAGmN5cmwAKmdyZWsAOmxhdG4ASgAEAAAAAP//AAMAAAABAAQABAAAAAD//wADAAAAAQAE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AHIAdABzAG8AbgBMAGkAYwBlAG4AcwBlAGQAIAB1AG4AZABlAHIAIAB0AGgAZQAgAEEAcABhAGMAaABlACAATABpAGMAZQBuAHMAZQAsACAAVgBlAHIAcwBpAG8AbgAgADIALgAwAGgAdAB0AHAAOgAvAC8AdwB3AHcALgBhAHAAYQBjAGgAZQAuAG8AcgBnAC8AbABpAGMAZQBuAHMAZQBzAC8ATABJAEMARQBOAFMARQAtADIALgAwAFcAZQBiAGYAbwBuAHQAIAAxAC4AMABUAGgAdQAgAEEAcAByACAAIAAyACAAMQA1ADoAMAAwADoAMgA0ACAAMgAwADIAMABkAGUAZgBhAHUAbAB0AGwAZQBvAEYAbwBuAHQAIABTAHEAdQBpAHIAcgBlAGwAAAACAAAAAAAA/XYAZAAAAAAAAAAAAAAAAAAAAAAAAAAAAOsAAAECAQMBBAADAAQABQAGAAcACAAJAAoACwAMAA0ADgAPABAAEQASABMAFAAVABYAFwAYABkAGgAbABwAHQAeAB8AIAAhACIAIwAkACUAJgAnACgAKQAqACsALAAtAC4ALwAwADEAMgAzADQANQA2ADcAOAA5ADoAOwA8AD0APgA/AEAAQQBCAEMARABFAEYARwBIAEkASgBLAEwATQBOAE8AUABRAFIAUwBUAFUAVgBXAFgAWQBaAFsAXABdAF4AXwBgAGEBBQCjAIQAhQC9AJYA6ACGAI4AiwCdAKkApAEGAIoA2gCDAJMBBwEIAI0AlwCIAMMA3gEJAJ4AqgD1APQA9gCiAK0AyQDHAK4AYgBjAJAAZADLAGUAyADKAM8AzADNAM4A6QBmANMA0ADRAK8AZwDwAJEA1gDUANUAaADrAO0AiQBqAGkAawBtAGwAbgCgAG8AcQBwAHIAcwB1AHQAdgB3AOoAeAB6AHkAewB9AHwAuAChAH8AfgCAAIEA7ADuALoAsACxALsA2ADZAQoBCwEMAQ0BDgEPARABEQESARMBFAEVARYBFwCyALMAtgC3AMQAtAC1AMUAhwCrARgAvgC/ARkBGgCMARsBHAEdAR4BHwZnbHlwaDEHdW5pMDAwRAd1bmkwMDAyB3VuaTAwQTAHdW5pMDBBRAd1bmkwMEIyB3VuaTAwQjMHdW5pMDBCOQd1bmkyMDAwB3VuaTIwMDEHdW5pMjAwMgd1bmkyMDAzB3VuaTIwMDQHdW5pMjAwNQd1bmkyMDA2B3VuaTIwMDcHdW5pMjAwOAd1bmkyMDA5B3VuaTIwMEEHdW5pMjAxMAd1bmkyMDExCmZpZ3VyZWRhc2gHdW5pMjAyRgd1bmkyMDVGBEV1cm8HdW5pMjVGQwd1bmlGQjAxB3VuaUZCMDIHdW5pRkIwMwd1bmlGQjA0ALgB/4WwAY0AS7AIUFixAQGOWbFGBitYIbAQWUuwFFJYIbCAWR2wBitcWACwAyBFsAMrRLAGIEWyA7ACK7ADK0SwBSBFsgZVAiuwAytEsAQgRbIFLgIrsAMrRLAHIEW6AAMBGAACK7ADK0SwCCBFsgeVAiuwAytEsAkgRbIIOgIrsAMrRLAKIEWyCR0CK7ADK0QBsAsgRbADK0SwDiBFsguQAiuxA0Z2K0SwDSBFsg5GAiuxA0Z2K0SwDCBFsg0wAiuxA0Z2K0SwDyBFugALf/8AAiuxA0Z2K0SwECBFsg/FAiuxA0Z2K0SwESBFshAvAiuxA0Z2K0RZsBQrAA==) format('truetype');
}

body
{
/* Re-adding horizontal scrollbar
    overflow-x: hidden;
    background-color: #f7f7f7;
*/
    background-color: #f3f3f0;
    color: #58544f;
    margin-top: 0px;
}

.isHidden { display: none; }

.page-root
{
	/*width: 1880px;*/
    /* Made this bigger to better match actual width and avoid flickering due to the horizontal Scrollbar showing up */
	width: 1903px;
	overflow: visible;
	 margin: 0 auto;
    position: relative;
}
.page-root-vertical
{
	width: 1056px;
	overflow: visible;
	  margin: 0 auto;
    position: relative;
}
.page-column-main { width: 930px; position: absolute;}
.page-column-detail { position: absolute; left: 1005.0px; }
.page-all-summaries { position: absolute; top:160px; left: -12px; width: 960px; }

.pos-feature-summary
{
	width: 1056px;
	height:162px;
    position: relative;
}

.container-feature-summary
{
	width: 1056px;
	height:175px;
    position: absolute;
}
.container-feature-summary-target
{
	width: 1056px;
	height:175px;
    position: relative;
}
.container-feature-detail
{
    height:900px;position:sticky;top:0;
    transform: scale(1.0);transform-origin: 0 0;
}
.container-feature-detail-vertical
{
    width: 900px;height:900px;position:absolute; top: 151px; left:93px
}
.container-feature-detail__offset
{
    height:900px;position:absolute;top:0px;left:-17px
}

.color-source { color: #0088ed; }
.button-border-source { border:1px solid #0088ed; }
.color-source-target { color: #004bd1; }
.color-compare { color: #f77721; }
.button-border-compare { border:1px solid #f77721; }
.color-compare-target { color: #e54600; }
.color-normal { color: #58544f; }
.color-target-summary { color: #CFC8BC; }
.color-light { color: #837d76; }
.color-red { color: #ff0000; }
.dim { opacity: 0.5; }
.color-title-disabled  { color: #e2e2e2; }

a { color: #58544f; }
.text-dataframe-title { font-family: RobotoBoldCond; font-size: 24px; }
.text-dataframe-title-small { font-family: RobotoBoldCond; font-size: 20px; }
.text-large-bold { font-family: RobotoBoldCond; font-size: 15.4px; }
.text-med-bold { font-family: RobotoBoldCond; font-size: 12px; }
.text-med { font-family: RobotoMed; font-size: 12px; }
.text-small-med { font-family: RobotoMed; font-size: 10px; }
.text-small-bold { font-family: RobotoBoldCond; font-size: 10px; }
.text-label { font-family: RobotoReg; font-size: 11px;}
.text-value { font-family: RobotoMed; font-size: 11px; }
.text-distinct { font-family: RobotoMed; font-size: 12px; font-weight: bold;}
.text-version { font-family: RobotoReg; font-size: 14px; font-weight: bold; }
.text-credits { font-family: RobotoReg; font-size: 9px;}

.pos-logo-group         { position: absolute; top:0px; left:0px; width: 380px; height: 200px; text-align: center;}
.pos-logo               { position: relative;
      margin-left: auto;
  margin-right: auto;
    top: 32px; }
.pos-credits            { position: relative; top:26px; text-align: center; }

.row-colored            { background-color: #00000008; }
.row-missing            { background-color: #00000008; text-indent: 4px; height: 16px; width: 250px; }
.assoc-row              { height: 13px; line-height: 11px; text-indent: 4px; }
.assoc-row-target       { height: 13px; line-height: 11px; text-indent: 4px; background-color: #221F1F; color: #c1b9af; }
.row-numeric-summary    { height: 13px; line-height: 11px; width: 140px; }
.row-separator-bottom   { border-bottom: 1px solid #00000018; }
.row-separator-top      { border-top: 1px solid #00000018; }
.breakdown-row          { height: 13px; line-height: 11px; text-indent: 4px; }
.breakdown-row-header   { height: 26px; text-indent: 4px; }
.breakdown-row-header-2-lines   { height: 30px; text-indent: 4px; }
.breakdown-hr           { position:absolute; top: 13px; left: 10px; width: 592px; }
.breakdown-hr-2-lines   { position:absolute; top: 20px; left: 10px; width: 592px; }

/* TAB ICON/NAME */
.text-title-tab                     { font-family: RobotoBoldCond; font-size: 15.4px; position: absolute; left: 74px; top: 24px; width:250px; }
.pos-tab-image                      { position: absolute; left: 45px; top: 21px; }
.pos-detail-tab-icon-text__offset    { position: absolute; left: -4px; top: -4px; }
.pos-text-title-tab__no-icon { position: absolute; left: 37px; top: 17px; }

/*
 DATAFRAME SUMMARY
------------------------------------*/
.pos-dataframe-summary-title-source { position: absolute; left: 0px; top: 12px; width: 250px; text-align: right; }
.pos-dataframe-summary-title-compare { position: absolute; left: 350px; top: 12px; width: 250px; text-align: left; }
.pos-dataframe-summary-title-compare-none { position: absolute; left: 350px; top: 16px; width: 250px; text-align: left; }
.pos-dataframe-summary  { position: absolute; top: 9px; left: 380px; }
.pos-dataframe-summary-rows  { position: absolute; top: 47px; left: 19px; }
.dataframe-summary-row  { height: 13px; width: 563px; line-height: 12px; }
.pos-df-summary-source      { position: absolute; left: 0px; width: 231px; text-align: right;}
.pos-df-summary-center     { position: absolute; left: 231px; width: 100px; text-align: center;}
.pos-df-summary-compare      { position: absolute; left: 331px; width: 200px; text-align: left;}
.size-df-summary-button     { width: 156px; height: 35px; }
.pos-df-summary-button-assoc-source { position: absolute; top: 54px; left: 10px; }
.pos-df-summary-button-assoc-compare { position: absolute; top: 54px; left: 397px; }

/*
 FEATURE SUMMARY
------------------------------------*/
.summary-number
{
    position: absolute; top: 17px; left: 0px; width: 34px;
    font-family: RobotoBoldCond; font-size: 26px;
    color: #d9d9d9; text-align: right;
}
.summary-number-vertical
{
    position: absolute; top: 25px; left: 6px; width: 34px;
    font-family: RobotoBoldCond; font-size: 26px;
    color: #d9d9d9; text-align: right;
    text-orientation: mixed;
    writing-mode: vertical-rl;
}

/* BASE STATS */
.pos-base-stats                 { position: absolute; top: 65px; left: 74px; }
.pos-base-stats-in-detail       { position: absolute; top: 49px; left: 68px; }
.base-stats-row                 { height: 13px; width: 200px; }
.pos-base-stats__label         { position: absolute; left: 0px; text-align: left;}
.pos-base-stats__source        { position: absolute; left: 55px; width: 55px; text-align: right;}
.pos-base-stats__source-perc   { position: absolute; left: 113px; width: 35px; text-align: right;}
.pos-base-stats__compare       { position: absolute; left: 153px; width: 55px; text-align: right;}
.pos-base-stats__compare-perc  { position: absolute; left: 211px; width: 35px; text-align: right;}

/* These are all NUMERICAL SUMMARY actually! */
.pos-summary-numeric-group1             { position: absolute; top: 67px; left: 372px; }
.pos-summary-numeric-group2             { position: absolute; top: 67px; left: 560px; }
.pos-summary-numeric-source          { position: absolute; left: 40px; width: 50px; text-align: right;}
.pos-summary-numeric-compare         { position: absolute; left: 90px; width: 50px; text-align: right;}
.pos-summary-numeric-source-wide          { position: absolute; left: 40px; width: 64px; text-align: right;}
.pos-summary-numeric-compare-wide         { position: absolute; left: 104px; width: 64px; text-align: right;}
.pos-detail-num__top                  { position: absolute; top: 63px; line-height: 13px; }
.pos-detail-num-col1__labels          { left: 320px; text-align: left; }
.pos-detail-num-col1__source          { right: 636px; text-align: right;}
.pos-detail-num-col1__compare         { right: 581px; text-align: right; }
.pos-detail-num-col2__labels          { left: 520px; text-align: left; }
.pos-detail-num-col2__source          { right: 441px; text-align: right;}
.pos-detail-num-col2__compare         { right: 386px; text-align: right; }

.pos-summary-text   { position: absolute; left: 372px; top: 67px; }
.summary-text       { overflow: hidden; text-overflow: ellipsis; position: absolute; height: 14px; white-space: nowrap; }

.pos-minigraph-cat      { position: absolute; right: 40px; top: 62px; }
.pos-minigraph-numeric  { position: absolute; right: 40px; top: 62px; }

.selector {}
.selector__body { z-index:10; position: absolute;  left: 0px; top:40px; width: 1040px; height: 134px; }
.selector__bottom { z-index:10; position: absolute;  left: 305px; top:174px; width: 735px; height: 22px; }
.selector__top { z-index:10; position: absolute;  left: 0px; top:16px; width: 305px; height: 24px; }

/*
DETAILS
------------------------------------*/
.pos-detail-cat-graph                 { position: absolute; left: 45px; top: 120px; }
.pos-detail-cat-breakdown             { position: absolute; left: 44px; overflow: hidden; }
.pos-detail-num-graph                 { position: absolute; left: 50px; top: 78px; }
.pos-detail-num-buttons               { position: absolute; left: 400px; top: 46px; width: 212px; }

.pos-detail-assoc-graph               { position: absolute; left: 28px; top: 84px; }
.pos-detail-assoc-desc-text           { position: absolute; left: 37px; top: 41px;     width: 800px;     line-height: 11px;}

.pos-detail-text                   { position: absolute; left: 45px; top: 75px; }

/* DETAIL LISTS */
.container-detail-assoc               { position: absolute; left: 40px; top: 27px; width: 215px;}
.pos-detail-num-most               { position: absolute; left: 20px; top: 606px; }
.pos-detail-num-min               { position: absolute; left: 313px; top: 606px; }
.pos-detail-num-max               { position: absolute; left: 607px; top: 606px; }
.pos-detail-num-label               { position: absolute; left: 0px; width: 56px; }
.pos-detail-num-source-pair         { position: absolute; width: 84px; left: 53px;}
.pos-detail-num-compare-pair         { position: absolute; width: 84px; left: 135px;}
.pos-detail-num-pair-pos__num      { position: absolute; left: 0px; width: 42px; text-align: right;}
.pos-detail-num-pair-pos__perc     { position: absolute; left: 49px; width: 30px; text-align: right; }

/* Number, percentage pairs in CATEGORICAL breakdown */
.pair__col          { position: absolute; width: 84px; }
.pair__header       { position: absolute; width: 79px; text-align: center;}
.pair-pos__num      { position: absolute; left: 0px; width: 42px; text-align: right;}
.pair-pos__perc     { position: absolute; left: 49px; width: 30px; text-align: right; }

/* DETAIL-ASSOC */
.pos-detail-cat-assoc-1              { position: absolute; left: 618px; top: 28px; width: 275px;}
.pos-detail-cat-assoc-CN              { position: absolute; left: 618px; top: 565px; width: 275px;}
.pos-assoc-row__label             { position: absolute; left: 0px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; width: 156px;}
.pos-assoc-row__source            { position: absolute; left: 150px; text-align: right; width: 30px; }
.pos-assoc-row__compare           { position: absolute; left: 120px; text-align: right; width: 30px; }

/* NUM-DETAIL COLS */
.pos-num-detail-row__label        { position: absolute; left: 0px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; width: 62px;}

hr { background-color: #58544f; height: 1px; border-width: 0px; }

button
{
	box-shadow:inset 0px 1px 0px 0px #ffffff;
	background:linear-gradient(to bottom, #f9f9f9 5%, #e9e9e9 100%);
	background-color:#f9f9f9;
	border-radius:6px;
	border:1px solid #dcdcdc;
	display:inline-block;
	cursor:pointer;
	color:#666666;
	font-family:Arial;
	font-size:10px;
	padding:3px 13px;
	text-decoration:none;
	text-shadow:0px 1px 0px #ffffff;
}
.button-assoc {
    outline: none;
}
.button-assoc:hover {
	border:2px solid #221f1f;
    outline: none;
}
.button-assoc:focus {
    outline: none;
}
.button-assoc-selected {
	border:2px solid #ff0000;
}
.button-assoc-selected:hover {
	border:2px solid #ff0000;
}
.button-assoc-selected:focus {
	border:2px solid #ff0000;
    outline: none;
}
 </style>

    <style>

                span.minigraph-f0::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f0-0::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f0-5::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f0-15::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f0-30::before { content: url(data:image/png;base64,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);}
                span.minigraph-f1::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f1-0::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f1-5::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f1-15::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f1-30::before { content: url(data:image/png;base64,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);}
                span.minigraph-f3::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f3-::before { content: url(data:image/png;base64,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);}
                span.minigraph-f4::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f4-::before { content: url(data:image/png;base64,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);}
                span.minigraph-f5::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f5-::before { content: url(data:image/png;base64,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);}
                span.minigraph-f6::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f6-::before { content: url(data:image/png;base64,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);}
                span.minigraph-f7::before { content: url(data:image/png;base64,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);}
                    span.detail_graph-f7-::before { content: url(data:image/png;base64,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);}
            span.association-graph-source::before { content: url(data:image/png;base64,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);}
            span.association-graph-compare::before { content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAABkCAYAAABw4pVUAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjQuMywgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/MnkTPAAAACXBIWXMAAA9hAAAPYQGoP6dpAAADMklEQVR4nO3dv2sTcRzG8XfD0U5RUlGoVBxcxEUnQQRFXBxvOcuJPxYRdHfoJOrQRZydtINwwyne5OrmXyAWBxGxreAg1QoSEeKQhMaQu6atuXtsnhcEkubb8uHeNCQHl+9Eq9XCdNSqHsD+5iBiHESMg4hxEDEOIsZBxNTiKFyKo/Bc1YNYWw14DjyNo3Cy6mGsHeQRcBA4UvEsBgTAWuf+fmCpf0EchVPAVN+Pp4GvI51s96kDq0maFZ6rCnru5y2cB+78q6nG3CywUrQgAPZ07n/JWbMAPOx5XAeWO398fYcDjovuMdv0eAXAjc7i94MWJGnWBJrdx3EUdu+uJ2n2fYeDjoWeY7apGnARuJyk2e9RDWTDC5I0O1b1ELbBn9TFOIgYBxHjIGIcRIyDiHEQMQ4ixkHEOIgYBxHjIGIcRIyDiHEQMQ4ixkHEOIgYBxHjIGIcRIyDiHEQMQ4ixkHEOIgYBxHjIGIcREwQR2H3yql6kmY/Kp3GCIAGgGNoCJI0W6t6CNsQxFG4BNxL0iwZtGDAVbj1UiYbUzUgARbjKJzJWTMPfOu5LZc021iqAQ+ASeBozpoFYG/Pbbac0cZTAFwFfgHvBi0ouArXRqAG3AauJGm2WvUw1n6X5e84EeJP6mIcRIyDiHEQMQ4ixkHEOIgYBxHjIGIcRIyDiHEQMQ4ixkHEOIgYBxHjIGIcRIyDiHEQMQ4ixkHEOIgYBxHjIGIcRIyDiHEQMQ4ixnvhivFeuGK8F66Y7eyF270Kt+7L24Y29JXLO9kL11fjbt00ULg76m7aC1d1LtiYbdMdtnfNXriqc4H3wv2veS9cMdv5pN4E7tLzMiZCdS7YwmwTrVbemyurgs9liXEQMUHeE3EUztH+DNIAXgA3O2+Bu883gMfAeWAFuJWk2avRjjv0bKeA132/VspXGMZReAC4BFyj/R0yb/qeLzxuA/9D4ijcBzwB7gOngQvA9b5l88Ah4DglnqAccrYZ4BPtYA2gUVKMOvARmANO5CwrPG55L1kngQlgMUmzt8BL4EzfmrPAsyTNPlDuCcphZpsBPidptta9lTAXwE/gMBAXrCk8bn8A8lnc5yIoh+wAAAAASUVORK5CYII=);}
        span.graph-legend { content: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAlgAAAAbCAYAAACgNfE3AAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjQuMywgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/MnkTPAAAACXBIWXMAAA9hAAAPYQGoP6dpAAADbElEQVR4nO3dSYhcRRzH8W8lQVzAiSUxDEiIImoEF1AE1+hF9KBoBHEBM6CCB4W4PkMQEiRCgaDmogQ3FA0keBAlYFDEDRRE4wIyqBjFRDxYTjBhHIkpD/WGaccYx/h0ejLfDzTd/bpeveo+/fr/L7pDKQVJkiR1Z850L0CSJOlgY8CSJEnqmAFLkiSpY/OmewHSvoSULwLeaJ/+3D5eUZr49X7OGQJ2lCZu+ZsxT086/Ghp4op/sVxJkv7ACpb63bHAWcAo8GZI+cj9jB0CLpnCnBk4que2svfFkHI4oJVKktSygqV+t7M0cXtI+SZgO3BDSHkUWAUMUitb1wObgKXA0pDyodTQtA64HPgNWFuauK6ds5QmjvReJKS8GlgO/ApsDikn4DHgYmAncE9p4saQ8jPAicBhwHHAE9QvKkPA98Cy0sThkPISaqXsVOADYHlp4rZOPxlJUt8yYGlGKE3cHVIeBs4G5gJ3A1uB14FbgKuBV4GPgHuB84Ex4BzgdGBjSPmFdroYUh7pmf6U9n4+cBnwGXAF8CVwB3AVsD6kvKkdd3T7+rnAU8CDwBnAS8DtwG3Ai8ArwDXAauAR4Mp9vbeQ8n/+WymliVblJOl/ZItQM80vwGvAGuBDYDEwWJq4G9gDjJUmjgLvUoPYFuBJIAAL2zlGqIFo/PZDe/yr0sT3ShN3UYPbIuAt4AFgADi8HfdpaeIwE3vENpQmfgt8DCwMKR8PLAFuBT4BrgXO7O4jkCT1OytYmhFCykcAJwGbqa23u4CXgeep4WmyO4FLgeva52/3jNs7uV0XUp58/lpqK3AZcAKw4S+u86elAnvbxzdSq2xQ25SSpFnCCpb63UBI+WRqqBqvLM0BtgELqPugxo0Bi0LKkdru20XdF3XeAVx3PvAT8CO1zfhPfAN8AdwMFOACJoKeJGkWMGCp330HvA8cAlxYmvgO8BDwLPA4NcwMtmOfo+6huh94mNoK3AqcRq0qDTJ1a4BjqHu6FrTHpnR+aWKhVr4GgM+B+5hoJ0qSZoHgfxFK08tN7pJ08DFgSZIkdcwWoSRJUscMWJIkSR0zYEmSJHXMgCVJktQxA5YkSVLHDFiSJEkdM2BJkiR1zIAlSZLUMQOWJElSxwxYkiRJHTNgSZIkdcyAJUmS1DEDliRJUsd+B1jEyJq3er2ZAAAAAElFTkSuQmCC);}
    </style>
<script>
    g_height = 1616;
    g_scale = 1.0;
</script>
</head>

<body>
<div class="page-root">
    <!-- TOP HEADER -->
    <!-- ALL SUMMARY TABS -->
    <div class="page-column-main" id="col1" style="transform: scale(1.0);transform-origin: 0 0;">
        <!-- DF Summary -->

        <!-- ASSOCIATIONS (VERTICAL ONLY) -->

        <!-- ALL SUMMARIES -->
       <div class="container-feature-summary" id="summary-df" data-detail-div="detail-df">
    <div class="pos-dataframe-summary text-label">
        <span class="top-header"></span>
        <div class="pos-dataframe-summary-title-source text-dataframe-title color-source">DataFrame</div>
            <div class="pos-dataframe-summary-title-compare-none text-dataframe-title-small color-title-disabled">NO COMPARISON TARGET</div>
        <div class="pos-dataframe-summary-rows">
            <div class="dataframe-summary-row row-colored">
                <div class="pos-df-summary-source color-source">7424</div>
                <div class="pos-df-summary-center">ROWS</div>
                <div class="pos-df-summary-compare color-compare"></div>
            </div>
             <div class="dataframe-summary-row">
                <div class="pos-df-summary-source color-source">10</div>
                <div class="pos-df-summary-center">DUPLICATES</div>
                <div class="pos-df-summary-compare color-compare"></div>
            </div>
            <div class="dataframe-summary-row row-colored">
                <div class="pos-df-summary-source color-source">1.6 MB</div>
                <div class="pos-df-summary-center">RAM</div>
                <div class="pos-df-summary-compare color-compare"></div>
            </div>
            <div class="dataframe-summary-row row">
                <div class="pos-df-summary-source color-source">
                    8
                </div>
                <div class="pos-df-summary-center">FEATURES</div>
                <div class="pos-df-summary-compare color-compare">
                </div>
            </div>
            <div class="dataframe-summary-row row-colored">
                <div class="pos-df-summary-source color-source">5</div>
                <div class="pos-df-summary-center">CATEGORICAL</div>
                <div class="pos-df-summary-compare color-compare"></div>
            </div>
             <div class="dataframe-summary-row ">
                <div class="pos-df-summary-source color-source">2</div>
                <div class="pos-df-summary-center">NUMERICAL</div>
                <div class="pos-df-summary-compare color-compare"></div>
            </div>
            <div class="dataframe-summary-row row-colored">
                <div class="pos-df-summary-source color-source">1</div>
                <div class="pos-df-summary-center">TEXT</div>
                <div class="pos-df-summary-compare color-compare"></div>
            </div>
            <button class="button-assoc color-source button-border-source size-df-summary-button pos-df-summary-button-assoc-source" id="button-summary-associations-source"
                data-detail-div="df-assoc-source">ASSOCIATIONS</button >
        </div>
    </div>
</div>



            <div class="pos-logo-group">
                <div class="pos-logo im-logo"></div>
                <div class="pos-credits text-credits">
                    <span class="text-version">2.1.4<br>
                    <a href="https://github.com/fbdesignpro/sweetviz">Get updates, docs & report issues here</a></span><br>
                    Created & maintained by <a href="https://www.fbdesignpro.com">Francois Bertrand</a> <br>
                    Graphic design by <a href="https://www.fbdesignpro.com" data-reach="Jeff is working on his contact info :)">Jean-Francois Hains</a>
                </div>
            </div>
        <div class="page-all-summaries">
            <span class="graph-legend" style="left: 391px;position: absolute;top: 5px;"></span>
            <!-- TARGET Summary -->
            <!-- FEATURE Summaries -->
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f0"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f0" data-rollover-span="rollover-f0"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f0" data-rollover-span="rollover-f0"></div>
    <div class="selector selector__top" data-detail-div="detail-f0" data-rollover-span="rollover-f0"></div>
    <span class="bg-tab-summary" style="z-index: -20000"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f0" style="z-index: -19999"></span>
    <div class="summary-number"
        >
        1
    </div>
    <div class="pos-tab-image ic-numeric"></div>
    <span class="text-title-tab color-normal">Category</span>

    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                33
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (<1%)
            </div>
        </div>
            <div class="base-stats-row">
            </div>
            <div class="base-stats-row">
                <div class="text-label color-normal pos-base-stats__label ">ZEROES:</div>
                <div class="text-value color-source pos-base-stats__source">
                        59
                </div>
                <div class="text-value color-source pos-base-stats__source-perc">
                        (<1%)
                </div>
            </div>
    </div>

    <div class="pos-summary-numeric-group1">
        <div class="row-numeric-summary  row-separator-bottom ">
            <div class="text-label" style="position:absolute">MAX</div>
            <div class="pos-summary-numeric-source text-value color-source">32.0</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">95%</div>
            <div class="pos-summary-numeric-source text-value color-source">29.0</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">Q3</div>
            <div class="pos-summary-numeric-source text-value color-source">24.0</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">AVG</div>
            <div class="pos-summary-numeric-source text-value color-source">16.6</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">MEDIAN</div>
            <div class="pos-summary-numeric-source text-value color-source">14.0</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">Q1</div>
            <div class="pos-summary-numeric-source text-value color-source">11.0</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">5%</div>
            <div class="pos-summary-numeric-source text-value color-source">4.0</div>
        </div>
        <div class="row-numeric-summary row-separator-top  ">
            <div class="text-label" style="position:absolute">MIN</div>
            <div class="pos-summary-numeric-source text-value color-source">0.0</div>
        </div>
    </div>
    <div class="pos-summary-numeric-group2">
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">RANGE</div>
                <div class="pos-summary-numeric-source text-value color-source">32.0</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">IQR</div>
                <div class="pos-summary-numeric-source text-value color-source">13.0</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">STD</div>
                <div class="pos-summary-numeric-source text-value color-source">8.14</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">VAR</div>
                <div class="pos-summary-numeric-source text-value color-source">66.3</div>
        </div>
        <div class="row-numeric-summary">
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">KURT.</div>
                <div class="pos-summary-numeric-source text-value color-source">-1.01</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">SKEW</div>
                <div class="pos-summary-numeric-source text-value color-source">0.203</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">SUM</div>
                <div class="pos-summary-numeric-source text-value color-source">123k</div>
        </div>
    </div>
    <span class="minigraph-f0 pos-minigraph-numeric"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f1"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f1" data-rollover-span="rollover-f1"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f1" data-rollover-span="rollover-f1"></div>
    <div class="selector selector__top" data-detail-div="detail-f1" data-rollover-span="rollover-f1"></div>
    <span class="bg-tab-summary" style="z-index: -19998"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f1" style="z-index: -19997"></span>
    <div class="summary-number"
        >
        2
    </div>
    <div class="pos-tab-image ic-numeric"></div>
    <span class="text-title-tab color-normal">Reviews</span>

    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                4,671
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (63%)
            </div>
        </div>
            <div class="base-stats-row">
            </div>
            <div class="base-stats-row">
                <div class="text-label color-normal pos-base-stats__label ">ZEROES:</div>
                <div class="text-value color-source pos-base-stats__source">
                        66
                </div>
                <div class="text-value color-source pos-base-stats__source-perc">
                        (<1%)
                </div>
            </div>
    </div>

    <div class="pos-summary-numeric-group1">
        <div class="row-numeric-summary  row-separator-bottom ">
            <div class="text-label" style="position:absolute">MAX</div>
            <div class="pos-summary-numeric-source text-value color-source">7.65</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">95%</div>
            <div class="pos-summary-numeric-source text-value color-source">5.93</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">Q3</div>
            <div class="pos-summary-numeric-source text-value color-source">4.57</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">MEDIAN</div>
            <div class="pos-summary-numeric-source text-value color-source">3.32</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">AVG</div>
            <div class="pos-summary-numeric-source text-value color-source">3.30</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">Q1</div>
            <div class="pos-summary-numeric-source text-value color-source">2.00</div>
        </div>
        <div class="row-numeric-summary   ">
            <div class="text-label" style="position:absolute">5%</div>
            <div class="pos-summary-numeric-source text-value color-source">0.78</div>
        </div>
        <div class="row-numeric-summary row-separator-top  ">
            <div class="text-label" style="position:absolute">MIN</div>
            <div class="pos-summary-numeric-source text-value color-source">0.00</div>
        </div>
    </div>
    <div class="pos-summary-numeric-group2">
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">RANGE</div>
                <div class="pos-summary-numeric-source text-value color-source">7.65</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">IQR</div>
                <div class="pos-summary-numeric-source text-value color-source">2.57</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">STD</div>
                <div class="pos-summary-numeric-source text-value color-source">1.62</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">VAR</div>
                <div class="pos-summary-numeric-source text-value color-source">2.63</div>
        </div>
        <div class="row-numeric-summary">
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">KURT.</div>
                <div class="pos-summary-numeric-source text-value color-source">-0.811</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">SKEW</div>
                <div class="pos-summary-numeric-source text-value color-source">0.069</div>
        </div>
        <div class="row-numeric-summary">
                <div class="text-label" style="position:absolute">SUM</div>
                <div class="pos-summary-numeric-source text-value color-source">24,530</div>
        </div>
    </div>
    <span class="minigraph-f1 pos-minigraph-numeric"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f2"
        style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f2" data-rollover-span="rollover-f2"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f2" data-rollover-span="rollover-f2"></div>
    <div class="selector selector__top" data-detail-div="detail-f2" data-rollover-span="rollover-f2"></div>
    <span class="bg-tab-summary" style="z-index: -19996"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f2" style="z-index: -19995"></span>
    <div class="summary-number"
        >
        3
    </div>
    <div class="pos-tab-image ic-text"></div>
    <span class="text-title-tab color-normal">Size</span>
    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                413
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (6%)
            </div>
        </div>
    </div>

    <div class="pos-summary-text">
        <div class="breakdown-row text-value " style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">154</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                14000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">152</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                13000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">151</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                12000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">150</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                11000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">149</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                15000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">126</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                17000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">125</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                25000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 618px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">6,417</div>
                <div class="pair-pos__perc">86%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 519px;">
                (Other)
            </div>
        </div>
    </div>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f3"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f3" data-rollover-span="rollover-f3"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f3" data-rollover-span="rollover-f3"></div>
    <div class="selector selector__top" data-detail-div="detail-f3" data-rollover-span="rollover-f3"></div>
    <span class="bg-tab-summary" style="z-index: -19994"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f3" style="z-index: -19993"></span>
    <div class="summary-number"
        >
        4
    </div>
    <div class="pos-tab-image ic-cat"></div>
    <span class="text-title-tab color-normal ">Installs</span>
    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                19
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (<1%)
            </div>
        </div>
    </div>
    <span class="minigraph-f3 pos-minigraph-cat"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f4"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f4" data-rollover-span="rollover-f4"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f4" data-rollover-span="rollover-f4"></div>
    <div class="selector selector__top" data-detail-div="detail-f4" data-rollover-span="rollover-f4"></div>
    <span class="bg-tab-summary" style="z-index: -19992"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f4" style="z-index: -19991"></span>
    <div class="summary-number"
        >
        5
    </div>
    <div class="pos-tab-image ic-cat"></div>
    <span class="text-title-tab color-normal ">Type</span>
    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                2
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (<1%)
            </div>
        </div>
    </div>
    <span class="minigraph-f4 pos-minigraph-cat"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f5"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f5" data-rollover-span="rollover-f5"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f5" data-rollover-span="rollover-f5"></div>
    <div class="selector selector__top" data-detail-div="detail-f5" data-rollover-span="rollover-f5"></div>
    <span class="bg-tab-summary" style="z-index: -19990"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f5" style="z-index: -19989"></span>
    <div class="summary-number"
        >
        6
    </div>
    <div class="pos-tab-image ic-cat"></div>
    <span class="text-title-tab color-normal ">Price</span>
    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                68
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (<1%)
            </div>
        </div>
    </div>
    <span class="minigraph-f5 pos-minigraph-cat"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f6"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f6" data-rollover-span="rollover-f6"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f6" data-rollover-span="rollover-f6"></div>
    <div class="selector selector__top" data-detail-div="detail-f6" data-rollover-span="rollover-f6"></div>
    <span class="bg-tab-summary" style="z-index: -19988"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f6" style="z-index: -19987"></span>
    <div class="summary-number"
        >
        7
    </div>
    <div class="pos-tab-image ic-cat"></div>
    <span class="text-title-tab color-normal ">Content Rating</span>
    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                6
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (<1%)
            </div>
        </div>
    </div>
    <span class="minigraph-f6 pos-minigraph-cat"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
                <div class="pos-feature-summary" style="top: 0.0px">
                    <div class="container-feature-summary" id="summary-f7"
     style="top: 0px">
    <div class="selector selector__body" data-detail-div="detail-f7" data-rollover-span="rollover-f7"></div>
    <div class="selector selector__bottom" data-detail-div="detail-f7" data-rollover-span="rollover-f7"></div>
    <div class="selector selector__top" data-detail-div="detail-f7" data-rollover-span="rollover-f7"></div>
    <span class="bg-tab-summary" style="z-index: -19986"></span>
    <span class="bg-tab-summary-rollover" id="rollover-f7" style="z-index: -19985"></span>
    <div class="summary-number"
        >
        8
    </div>
    <div class="pos-tab-image ic-cat"></div>
    <span class="text-title-tab color-normal ">Rating_category</span>
    <div class="pos-base-stats">
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label  ">VALUES:</div>
            <div class="text-value color-source pos-base-stats__source">
                7,424
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (100%)
            </div>
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
        <div class="base-stats-row">
        </div>
        <div class="base-stats-row">
            <div class="text-label color-normal pos-base-stats__label ">DISTINCT:</div>
            <div class="text-distinct color-source pos-base-stats__source">
                2
            </div>
            <div class="text-value color-source pos-base-stats__source-perc">
                (<1%)
            </div>
        </div>
    </div>
    <span class="minigraph-f7 pos-minigraph-cat"></span>
</div>
                    <!-- This DETAIL WINDOW (VERTICAL ONLY) -->
                </div>
        </div>
    </div>

    <!-- ALL DETAIL WINDOWS (WIDESCREEN ONLY) -->
        <div class="page-column-detail" id="col2">
                <div class="isHidden container-feature-detail" id="df-assoc-source"Yellow
>
<div class="container-feature-detail__offset"
>
    <span class="bg-tab-detail-wide"></span>
    <span class="text-title-tab pos-text-title-tab__no-icon">Associations</span>
    <div class="text-med  pos-detail-assoc-desc-text" style="font-size: 11px;">
        <span class="color-source">[Only including dataset "DataFrame"]</span><br>
         &#9632; <b>Squares</b> are categorical associations (uncertainty coefficient & correlation ratio) from 0 to 1. The uncertainty coefficient is <b>assymmetrical</b>,
        (i.e. ROW LABEL values indicate how much they PROVIDE INFORMATION to each LABEL at the TOP).
       <br><br>&#8226; <b>Circles</b> are the symmetrical numerical correlations (Pearson's) from -1 to 1. The <b>trivial diagonal</b> is intentionally left blank for clarity.
    </div>
    <span class="association-graph-source pos-detail-assoc-graph"></span>
</div>
</div>

                <div class="isHidden container-feature-detail" id="df-assoc-compare"Yellow
>
<div class="container-feature-detail__offset"
>
    <span class="bg-tab-detail-wide"></span>
    <span class="text-title-tab pos-text-title-tab__no-icon">Associations</span>
    <div class="text-med  pos-detail-assoc-desc-text" style="font-size: 11px;">
        <span class="color-compare">[Only including dataset "None"]</span><br>
         &#9632; <b>Squares</b> are categorical associations (uncertainty coefficient & correlation ratio) from 0 to 1. The uncertainty coefficient is <b>assymmetrical</b>,
        (i.e. ROW LABEL values indicate how much they PROVIDE INFORMATION to each LABEL at the TOP).
       <br><br>&#8226; <b>Circles</b> are the symmetrical numerical correlations (Pearson's) from -1 to 1. The <b>trivial diagonal</b> is intentionally left blank for clarity.
    </div>
    <span class="association-graph-compare pos-detail-assoc-graph"></span>
</div>
</div>

            <!-- TARGET Detail -->
            <!-- FEATURE Details -->
                <div class="isHidden container-feature-detail"
    id="detail-f0" >
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-numeric"></div>
            <span class="text-title-tab">Category</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <!-- BUTTONS -->
    <div class="pos-detail-num-buttons">
            <button class="button-bin" data-target="detail_graph-f0"
                data-new_class="detail_graph-f0-0">Auto </button>
            <button class="button-bin" data-target="detail_graph-f0"
                data-new_class="detail_graph-f0-5">5 </button>
            <button class="button-bin" data-target="detail_graph-f0"
                data-new_class="detail_graph-f0-15">15 </button>
            <button class="button-bin" data-target="detail_graph-f0"
                data-new_class="detail_graph-f0-30">30 </button>
    </div>

    <!-- GRAPH -->
    <span class="detail_graph-f0-0
        pos-detail-num-graph" id="detail_graph-f0"></span>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CN-f0">
        <span class="bg-extra-column"  <!-- expand if target in vertical layout -->
            ></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold">NUMERICAL ASSOCIATIONS</div>
            <div class="text-small-bold color-light" style="line-height: 10px">
                (PEARSON, -1 to 1)
            </div>
<!--             <div class="text-med-bold">Category</div>
            <div class="text-large-bold">CORRELATION RATIO WITH...</div>
-->
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Reviews</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
            <br>
            <div class="text-large-bold">CATEGORICAL ASSOCIATIONS</div>
            <div class="text-small-bold color-light" style="line-height: 10px">
                (CORRELATION RATIO, 0 to 1)
            </div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Content Rating</div>
                    <div class="pos-assoc-row__source text-label color-source">0.15</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Price</div>
                    <div class="pos-assoc-row__source text-label color-source">0.09</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Installs</div>
                    <div class="pos-assoc-row__source text-label color-source">0.06</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Rating_category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Type</div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
        </div>
    </div>
    <!-- FREQUENT -->
    <div class="pos-detail-num-most">
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold">MOST FREQUENT VALUES</div>
            <hr>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">11</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1,591</div>
                        <div class="pos-detail-num-pair-pos__perc">21.4%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">14</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">959</div>
                        <div class="pos-detail-num-pair-pos__perc">12.9%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">29</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">634</div>
                        <div class="pos-detail-num-pair-pos__perc">8.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">23</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">279</div>
                        <div class="pos-detail-num-pair-pos__perc">3.8%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">20</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">277</div>
                        <div class="pos-detail-num-pair-pos__perc">3.7%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">18</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">273</div>
                        <div class="pos-detail-num-pair-pos__perc">3.7%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">12</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">263</div>
                        <div class="pos-detail-num-pair-pos__perc">3.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">28</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">232</div>
                        <div class="pos-detail-num-pair-pos__perc">3.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">25</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">231</div>
                        <div class="pos-detail-num-pair-pos__perc">3.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">4</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">225</div>
                        <div class="pos-detail-num-pair-pos__perc">3.0%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">24</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">225</div>
                        <div class="pos-detail-num-pair-pos__perc">3.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">6</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">206</div>
                        <div class="pos-detail-num-pair-pos__perc">2.8%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">15</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">199</div>
                        <div class="pos-detail-num-pair-pos__perc">2.7%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">27</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">170</div>
                        <div class="pos-detail-num-pair-pos__perc">2.3%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">21</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">162</div>
                        <div class="pos-detail-num-pair-pos__perc">2.2%</div>
                    </div>
                </div>
        </div>
    </div>
    <!-- MINIMUM -->
    <div class="pos-detail-num-min">
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold"> SMALLEST VALUES</div>
            <hr>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">59</div>
                        <div class="pos-detail-num-pair-pos__perc">0.8%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">63</div>
                        <div class="pos-detail-num-pair-pos__perc">0.8%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">2</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">37</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">3</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">143</div>
                        <div class="pos-detail-num-pair-pos__perc">1.9%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">4</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">225</div>
                        <div class="pos-detail-num-pair-pos__perc">3.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">5</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">49</div>
                        <div class="pos-detail-num-pair-pos__perc">0.7%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">6</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">206</div>
                        <div class="pos-detail-num-pair-pos__perc">2.8%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">141</div>
                        <div class="pos-detail-num-pair-pos__perc">1.9%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">8</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">95</div>
                        <div class="pos-detail-num-pair-pos__perc">1.3%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">9</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">67</div>
                        <div class="pos-detail-num-pair-pos__perc">0.9%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">10</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">38</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">11</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1,591</div>
                        <div class="pos-detail-num-pair-pos__perc">21.4%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">12</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">263</div>
                        <div class="pos-detail-num-pair-pos__perc">3.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">13</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">82</div>
                        <div class="pos-detail-num-pair-pos__perc">1.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">14</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">959</div>
                        <div class="pos-detail-num-pair-pos__perc">12.9%</div>
                    </div>
                </div>
        </div>
    </div>
    <!-- MAXIMUM -->
    <div class="pos-detail-num-max">
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold">LARGEST VALUES</div>
            <hr>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">32</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">51</div>
                        <div class="pos-detail-num-pair-pos__perc">0.7%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">31</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">116</div>
                        <div class="pos-detail-num-pair-pos__perc">1.6%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">30</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">147</div>
                        <div class="pos-detail-num-pair-pos__perc">2.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">29</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">634</div>
                        <div class="pos-detail-num-pair-pos__perc">8.5%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">28</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">232</div>
                        <div class="pos-detail-num-pair-pos__perc">3.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">27</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">170</div>
                        <div class="pos-detail-num-pair-pos__perc">2.3%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">26</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">159</div>
                        <div class="pos-detail-num-pair-pos__perc">2.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">25</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">231</div>
                        <div class="pos-detail-num-pair-pos__perc">3.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">24</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">225</div>
                        <div class="pos-detail-num-pair-pos__perc">3.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">23</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">279</div>
                        <div class="pos-detail-num-pair-pos__perc">3.8%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">22</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">44</div>
                        <div class="pos-detail-num-pair-pos__perc">0.6%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">21</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">162</div>
                        <div class="pos-detail-num-pair-pos__perc">2.2%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">20</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">277</div>
                        <div class="pos-detail-num-pair-pos__perc">3.7%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">19</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">95</div>
                        <div class="pos-detail-num-pair-pos__perc">1.3%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">18</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">273</div>
                        <div class="pos-detail-num-pair-pos__perc">3.7%</div>
                    </div>
                </div>
        </div>
    </div>

</div>
</div>
                <div class="isHidden container-feature-detail"
    id="detail-f1" >
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-numeric"></div>
            <span class="text-title-tab">Reviews</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <!-- BUTTONS -->
    <div class="pos-detail-num-buttons">
            <button class="button-bin" data-target="detail_graph-f1"
                data-new_class="detail_graph-f1-0">Auto </button>
            <button class="button-bin" data-target="detail_graph-f1"
                data-new_class="detail_graph-f1-5">5 </button>
            <button class="button-bin" data-target="detail_graph-f1"
                data-new_class="detail_graph-f1-15">15 </button>
            <button class="button-bin" data-target="detail_graph-f1"
                data-new_class="detail_graph-f1-30">30 </button>
    </div>

    <!-- GRAPH -->
    <span class="detail_graph-f1-0
        pos-detail-num-graph" id="detail_graph-f1"></span>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CN-f1">
        <span class="bg-extra-column"  <!-- expand if target in vertical layout -->
            ></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold">NUMERICAL ASSOCIATIONS</div>
            <div class="text-small-bold color-light" style="line-height: 10px">
                (PEARSON, -1 to 1)
            </div>
<!--             <div class="text-med-bold">Reviews</div>
            <div class="text-large-bold">CORRELATION RATIO WITH...</div>
-->
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
            <br>
            <div class="text-large-bold">CATEGORICAL ASSOCIATIONS</div>
            <div class="text-small-bold color-light" style="line-height: 10px">
                (CORRELATION RATIO, 0 to 1)
            </div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Installs</div>
                    <div class="pos-assoc-row__source text-label color-source">0.96</div>
                </div>
                <div class="assoc-row row-colored" style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Rating_category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.23</div>
                </div>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Content Rating</div>
                    <div class="pos-assoc-row__source text-label color-source">0.21</div>
                </div>
                <div class="assoc-row row-colored" style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Price</div>
                    <div class="pos-assoc-row__source text-label color-source">0.18</div>
                </div>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Type</div>
                    <div class="pos-assoc-row__source text-label color-source">0.17</div>
                </div>
        </div>
    </div>
    <!-- FREQUENT -->
    <div class="pos-detail-num-most">
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold">MOST FREQUENT VALUES</div>
            <hr>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.3010299956639812</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">81</div>
                        <div class="pos-detail-num-pair-pos__perc">1.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.47712125471966244</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">75</div>
                        <div class="pos-detail-num-pair-pos__perc">1.0%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.6989700043360189</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">74</div>
                        <div class="pos-detail-num-pair-pos__perc">1.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.6020599913279624</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">72</div>
                        <div class="pos-detail-num-pair-pos__perc">1.0%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.0</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">66</div>
                        <div class="pos-detail-num-pair-pos__perc">0.9%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.8450980400142568</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">61</div>
                        <div class="pos-detail-num-pair-pos__perc">0.8%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.7781512503836436</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">60</div>
                        <div class="pos-detail-num-pair-pos__perc">0.8%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.9030899869919435</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">53</div>
                        <div class="pos-detail-num-pair-pos__perc">0.7%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.0791812460476249</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">51</div>
                        <div class="pos-detail-num-pair-pos__perc">0.7%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.0</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">44</div>
                        <div class="pos-detail-num-pair-pos__perc">0.6%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.0413926851582251</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">39</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.9542425094393249</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">38</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.1139433523068367</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">37</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.2304489213782739</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">35</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.2787536009528289</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">32</div>
                        <div class="pos-detail-num-pair-pos__perc">0.4%</div>
                    </div>
                </div>
        </div>
    </div>
    <!-- MINIMUM -->
    <div class="pos-detail-num-min">
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold"> SMALLEST VALUES</div>
            <hr>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.0</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">66</div>
                        <div class="pos-detail-num-pair-pos__perc">0.9%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.3010299956639812</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">81</div>
                        <div class="pos-detail-num-pair-pos__perc">1.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.47712125471966244</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">75</div>
                        <div class="pos-detail-num-pair-pos__perc">1.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.6020599913279624</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">72</div>
                        <div class="pos-detail-num-pair-pos__perc">1.0%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.6989700043360189</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">74</div>
                        <div class="pos-detail-num-pair-pos__perc">1.0%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.7781512503836436</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">60</div>
                        <div class="pos-detail-num-pair-pos__perc">0.8%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.8450980400142568</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">61</div>
                        <div class="pos-detail-num-pair-pos__perc">0.8%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.9030899869919435</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">53</div>
                        <div class="pos-detail-num-pair-pos__perc">0.7%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">0.9542425094393249</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">38</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.0</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">44</div>
                        <div class="pos-detail-num-pair-pos__perc">0.6%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.0413926851582251</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">39</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.0791812460476249</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">51</div>
                        <div class="pos-detail-num-pair-pos__perc">0.7%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.1139433523068367</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">37</div>
                        <div class="pos-detail-num-pair-pos__perc">0.5%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.146128035678238</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">29</div>
                        <div class="pos-detail-num-pair-pos__perc">0.4%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">1.1760912590556813</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">25</div>
                        <div class="pos-detail-num-pair-pos__perc">0.3%</div>
                    </div>
                </div>
        </div>
    </div>
    <!-- MAXIMUM -->
    <div class="pos-detail-num-max">
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc">
            <div class="text-large-bold">LARGEST VALUES</div>
            <hr>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.65218721876379</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.652166274482339</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.6520668503422415</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.442877068642197</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.442857362675853</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.442843248393643</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.442828695007467</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.442663215813858</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.364302072354319</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.364265280073927</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.364241494833887</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.364086999863773</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.350832913664128</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row row-colored">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.350823774679102</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
                <div class="assoc-row ">
                    <div class="pos-num-detail-row__label text-label pos-detail-num-label">7.350799377294058</div>
                    <div class="pos-detail-num-source-pair color-source text-value">
                        <div class="pos-detail-num-pair-pos__num dim">1</div>
                        <div class="pos-detail-num-pair-pos__perc"><0.1%</div>
                    </div>
                </div>
        </div>
    </div>

</div>
</div>
                <div class="isHidden container-feature-detail"
     id="detail-f2">
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-wide" style="left: 12px"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-text"></div>
            <span class="text-title-tab">Size</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <div class="pos-detail-text"  >
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">154</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                14000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">152</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                13000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">151</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                12000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">150</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                11000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">149</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                15000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">126</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                17000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">125</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                25000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">112</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                16000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">112</div>
                <div class="pair-pos__perc">2%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                21000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">111</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                24000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">110</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                19000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">107</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                20000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">106</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                26000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">99</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                23000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">99</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                18000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">93</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                10000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">92</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                22000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">85</div>
                <div class="pair-pos__perc">1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                27000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">74</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                28000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">71</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                37000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">70</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                33000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">69</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                30000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">66</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                35000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">65</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                31000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">63</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                29000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">62</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.3000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">56</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                44000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">55</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                40000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">54</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                46000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">53</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                2.5000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">52</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                39000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">52</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                32000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">51</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                36000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">51</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                2.8000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">51</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.8000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">50</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                4.0000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">49</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                2.3000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">49</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                38000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">49</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.9000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">49</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                48000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">49</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                34000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">48</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                2.9000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">47</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.0000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">45</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.4000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">45</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.1000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">44</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                4.3000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">44</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                5.0000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">44</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                4.1000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">44</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.7000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">43</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.2000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">43</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                50000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">43</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                3.5000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">42</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                5.4000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">42</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                4.2000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">42</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                41000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">42</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                49000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">42</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                2.7000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">41</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                43000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">41</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                2.2000000
            </div>
        </div>
        <div class="breakdown-row text-value row-colored" style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">40</div>
                <div class="pair-pos__perc"><1%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                63000000
            </div>
        </div>
        <div class="breakdown-row text-value " style="width: 800px;">
            <div class="pair__col color-source">
                <div class="pair-pos__num dim">3,159</div>
                <div class="pair-pos__perc">43%</div>
            </div>
                <div class="pair__col color-compare" style="position: absolute; left: px">
                    <div class="pair-pos__num dim">-</div>
                    <div class="pair-pos__perc">-</div>
                </div>
            <div class="summary-text color-normal" style="left: 99px; width: 701px;">
                (Other)
            </div>
        </div>
    </div>
</div>
</div>

                <div class="isHidden container-feature-detail"
     id="detail-f3">
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-cat"></div>
            <span class="text-title-tab">Installs</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <span class="detail_graph-f3-
                pos-detail-cat-graph" id="detail_graph-f3"
    style="top: 75px;"></span>

    <div class="pos-detail-cat-breakdown " id="detail_breakdown-f3"
        style="top: 614.0px;"> <!-- height: 296.0px;"> WHY was this needed? Causes issue in vertical layout. -->
        <!-- HEADER ROW -->
        <div class="breakdown-row-header text-value" style="width:553px">
            <div class="text-med-bold" style="position: absolute; left:10px">TOP CATEGORIES</div>
            <div class="breakdown-hr"><hr></div>
            <div class="pair__header color-source" style="left: 102px"></div>
            <!-- Targets -->
                <div class="pair__header color-compare" style="position: absolute; left: px">
                    <!--None-->
                </div>
        </div>

        <!-- ROW CONTENT -->
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1,000,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">1,230</div>
                    <div class="pair-pos__perc">17%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">100,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">1,003</div>
                    <div class="pair-pos__perc">14%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">10,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">949</div>
                    <div class="pair-pos__perc">13%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">10,000,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">762</div>
                    <div class="pair-pos__perc">10%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">675</div>
                    <div class="pair-pos__perc">9%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">5,000,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">493</div>
                    <div class="pair-pos__perc">7%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">500,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">471</div>
                    <div class="pair-pos__perc">6%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">50,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">432</div>
                    <div class="pair-pos__perc">6%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">5,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">414</div>
                    <div class="pair-pos__perc">6%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">100</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">297</div>
                    <div class="pair-pos__perc">4%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">500</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">195</div>
                    <div class="pair-pos__perc">3%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">100,000,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">192</div>
                    <div class="pair-pos__perc">3%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">50,000,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">144</div>
                    <div class="pair-pos__perc">2%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">10</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">67</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">50</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">56</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">500,000,000</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">24</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">5</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">9</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">     (Other)</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">11</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
                <div class="breakdown-row text-value" style="width:553px">
                </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">ALL</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">7,424</div>
                    <div class="pair-pos__perc">100%</div>
                </div>
                <!-- Targets -->
            </div>
        <div id="detail_cat_end-3"></div>
    </div>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CC-f3">
        <!-- no background for target in vertical mode -->
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc " id="cat-assoc-window-f3">
            <!-- CAT-CAT -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                CATEGORICAL ASSOCIATIONS<br>
                (UNCERTAINTY COEFFICIENT, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Installs<br>
            PROVIDES INFORMATION ON...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Type<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.16</div>
                </div>
                <div class="assoc-row row-colored" style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Price<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.15</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Rating_category<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.08</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Content Rating<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
            <br>
            <div class="text-large-bold" style="line-height: 104%;">THESE FEATURES<br>GIVE INFORMATION<br>
            ON Installs:</div>
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Price</div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Type</div>
                    <div class="pos-assoc-row__source text-label color-source">0.02</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Rating_category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Content Rating</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
            <br>
            <!-- CAT-NUM -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                NUMERICAL ASSOCIATIONS<br>
                (CORRELATION RATIO, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Installs<br>
                    CORRELATION RATIO WITH...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Reviews</div>
                    <div class="pos-assoc-row__source text-label color-source">0.96</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.06</div>
                </div>
        </div>
    </div>
</div>
</div>
                <div class="isHidden container-feature-detail"
     id="detail-f4">
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-cat"></div>
            <span class="text-title-tab">Type</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <span class="detail_graph-f4-
                pos-detail-cat-graph" id="detail_graph-f4"
    style="top: 75px;"></span>

    <div class="pos-detail-cat-breakdown " id="detail_breakdown-f4"
        style="top: 204.0px;"> <!-- height: 706.0px;"> WHY was this needed? Causes issue in vertical layout. -->
        <!-- HEADER ROW -->
        <div class="breakdown-row-header text-value" style="width:553px">
            <div class="text-med-bold" style="position: absolute; left:10px">TOP CATEGORIES</div>
            <div class="breakdown-hr"><hr></div>
            <div class="pair__header color-source" style="left: 48px"></div>
            <!-- Targets -->
                <div class="pair__header color-compare" style="position: absolute; left: px">
                    <!--None-->
                </div>
        </div>

        <!-- ROW CONTENT -->
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">0</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">6,877</div>
                    <div class="pair-pos__perc">93%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">547</div>
                    <div class="pair-pos__perc">7%</div>
                </div>
                <!-- Targets -->
            </div>
                <div class="breakdown-row text-value" style="width:553px">
                </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">ALL</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">7,424</div>
                    <div class="pair-pos__perc">100%</div>
                </div>
                <!-- Targets -->
            </div>
        <div id="detail_cat_end-4"></div>
    </div>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CC-f4">
        <!-- no background for target in vertical mode -->
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc " id="cat-assoc-window-f4">
            <!-- CAT-CAT -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                CATEGORICAL ASSOCIATIONS<br>
                (UNCERTAINTY COEFFICIENT, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Type<br>
            PROVIDES INFORMATION ON...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Price<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.56</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Installs<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.02</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Content Rating<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Rating_category<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
            <br>
            <div class="text-large-bold" style="line-height: 104%;">THESE FEATURES<br>GIVE INFORMATION<br>
            ON Type:</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Price</div>
                    <div class="pos-assoc-row__source text-label color-source">1.00</div>
                </div>
                <div class="assoc-row row-colored" style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Installs</div>
                    <div class="pos-assoc-row__source text-label color-source">0.16</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Content Rating</div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Rating_category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
            <br>
            <!-- CAT-NUM -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                NUMERICAL ASSOCIATIONS<br>
                (CORRELATION RATIO, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Type<br>
                    CORRELATION RATIO WITH...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Reviews</div>
                    <div class="pos-assoc-row__source text-label color-source">0.17</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
        </div>
    </div>
</div>
</div>
                <div class="isHidden container-feature-detail"
     id="detail-f5">
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-cat"></div>
            <span class="text-title-tab">Price</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <span class="detail_graph-f5-
                pos-detail-cat-graph" id="detail_graph-f5"
    style="top: 75px;"></span>

    <div class="pos-detail-cat-breakdown " id="detail_breakdown-f5"
        style="top: 614.0px;"> <!-- height: 296.0px;"> WHY was this needed? Causes issue in vertical layout. -->
        <!-- HEADER ROW -->
        <div class="breakdown-row-header text-value" style="width:553px">
            <div class="text-med-bold" style="position: absolute; left:10px">TOP CATEGORIES</div>
            <div class="breakdown-hr"><hr></div>
            <div class="pair__header color-source" style="left: 102px"></div>
            <!-- Targets -->
                <div class="pair__header color-compare" style="position: absolute; left: px">
                    <!--None-->
                </div>
        </div>

        <!-- ROW CONTENT -->
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">0</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">6,877</div>
                    <div class="pair-pos__perc">93%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">0.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">104</div>
                    <div class="pair-pos__perc">1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">2.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">98</div>
                    <div class="pair-pos__perc">1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">4.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">61</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">53</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">3.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">42</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1.49</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">28</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">2.49</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">16</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">9.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">14</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">5.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">12</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">399.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">11</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">6.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">9</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">14.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">8</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">4.49</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">8</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">7.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">7</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">3.49</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">6</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">19.99</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">4</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">     (Other)</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">66</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
                <div class="breakdown-row text-value" style="width:553px">
                </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 102px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">ALL</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 102px">
                    <div class="pair-pos__num dim">7,424</div>
                    <div class="pair-pos__perc">100%</div>
                </div>
                <!-- Targets -->
            </div>
        <div id="detail_cat_end-5"></div>
    </div>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CC-f5">
        <!-- no background for target in vertical mode -->
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc " id="cat-assoc-window-f5">
            <!-- CAT-CAT -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                CATEGORICAL ASSOCIATIONS<br>
                (UNCERTAINTY COEFFICIENT, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Price<br>
            PROVIDES INFORMATION ON...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Type<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">1.00</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Installs<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Content Rating<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Rating_category<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
            <br>
            <div class="text-large-bold" style="line-height: 104%;">THESE FEATURES<br>GIVE INFORMATION<br>
            ON Price:</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Type</div>
                    <div class="pos-assoc-row__source text-label color-source">0.56</div>
                </div>
                <div class="assoc-row row-colored" style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Installs</div>
                    <div class="pos-assoc-row__source text-label color-source">0.15</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Content Rating</div>
                    <div class="pos-assoc-row__source text-label color-source">0.02</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Rating_category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
            <br>
            <!-- CAT-NUM -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                NUMERICAL ASSOCIATIONS<br>
                (CORRELATION RATIO, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Price<br>
                    CORRELATION RATIO WITH...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Reviews</div>
                    <div class="pos-assoc-row__source text-label color-source">0.18</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.09</div>
                </div>
        </div>
    </div>
</div>
</div>
                <div class="isHidden container-feature-detail"
     id="detail-f6">
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-cat"></div>
            <span class="text-title-tab">Content Rating</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <span class="detail_graph-f6-
                pos-detail-cat-graph" id="detail_graph-f6"
    style="top: 75px;"></span>

    <div class="pos-detail-cat-breakdown " id="detail_breakdown-f6"
        style="top: 443.99999999999994px;"> <!-- height: 466.00000000000006px;"> WHY was this needed? Causes issue in vertical layout. -->
        <!-- HEADER ROW -->
        <div class="breakdown-row-header text-value" style="width:553px">
            <div class="text-med-bold" style="position: absolute; left:10px">TOP CATEGORIES</div>
            <div class="breakdown-hr"><hr></div>
            <div class="pair__header color-source" style="left: 48px"></div>
            <!-- Targets -->
                <div class="pair__header color-compare" style="position: absolute; left: px">
                    <!--None-->
                </div>
        </div>

        <!-- ROW CONTENT -->
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">5,958</div>
                    <div class="pair-pos__perc">80%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">4</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">832</div>
                    <div class="pair-pos__perc">11%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">3</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">332</div>
                    <div class="pair-pos__perc">4%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">2</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">299</div>
                    <div class="pair-pos__perc">4%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">0</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">2</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">5</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">1</div>
                    <div class="pair-pos__perc"><1%</div>
                </div>
                <!-- Targets -->
            </div>
                <div class="breakdown-row text-value" style="width:553px">
                </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">ALL</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">7,424</div>
                    <div class="pair-pos__perc">100%</div>
                </div>
                <!-- Targets -->
            </div>
        <div id="detail_cat_end-6"></div>
    </div>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CC-f6">
        <!-- no background for target in vertical mode -->
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc " id="cat-assoc-window-f6">
            <!-- CAT-CAT -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                CATEGORICAL ASSOCIATIONS<br>
                (UNCERTAINTY COEFFICIENT, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Content Rating<br>
            PROVIDES INFORMATION ON...</div>
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Price<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.02</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Installs<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Rating_category<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Type<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
            <br>
            <div class="text-large-bold" style="line-height: 104%;">THESE FEATURES<br>GIVE INFORMATION<br>
            ON Content Rating:</div>
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Installs</div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Price</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Rating_category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Type</div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
            <br>
            <!-- CAT-NUM -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                NUMERICAL ASSOCIATIONS<br>
                (CORRELATION RATIO, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Content Rating<br>
                    CORRELATION RATIO WITH...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Reviews</div>
                    <div class="pos-assoc-row__source text-label color-source">0.21</div>
                </div>
                <div class="assoc-row row-colored" style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.15</div>
                </div>
        </div>
    </div>
</div>
</div>
                <div class="isHidden container-feature-detail"
     id="detail-f7">
<div class="container-feature-detail__offset">
        <span class="bg-tab-detail-med"></span>
        <div class="pos-detail-tab-icon-text__offset">
            <div class="pos-tab-image ic-cat"></div>
            <span class="text-title-tab">Rating_category</span>
        </div>
    <div class="pos-base-stats-in-detail">
        <div class="row-missing">
            <div class="text-label color-normal pos-base-stats__label">MISSING:</div>
            <div class="text-value color-source pos-base-stats__source">
                    ---
            </div>
            <div class="text-value color-source pos-base-stats__source-perc" >

            </div>
        </div>
</div>

    <span class="detail_graph-f7-
                pos-detail-cat-graph" id="detail_graph-f7"
    style="top: 75px;"></span>

    <div class="pos-detail-cat-breakdown " id="detail_breakdown-f7"
        style="top: 204.0px;"> <!-- height: 706.0px;"> WHY was this needed? Causes issue in vertical layout. -->
        <!-- HEADER ROW -->
        <div class="breakdown-row-header text-value" style="width:553px">
            <div class="text-med-bold" style="position: absolute; left:10px">TOP CATEGORIES</div>
            <div class="breakdown-hr"><hr></div>
            <div class="pair__header color-source" style="left: 48px"></div>
            <!-- Targets -->
                <div class="pair__header color-compare" style="position: absolute; left: px">
                    <!--None-->
                </div>
        </div>

        <!-- ROW CONTENT -->
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">0</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">6,599</div>
                    <div class="pair-pos__perc">89%</div>
                </div>
                <!-- Targets -->
            </div>
            <div class="breakdown-row text-value row-colored" style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">1</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">825</div>
                    <div class="pair-pos__perc">11%</div>
                </div>
                <!-- Targets -->
            </div>
                <div class="breakdown-row text-value" style="width:553px">
                </div>
            <div class="breakdown-row text-value " style="width:553px">
                <!-- Name -->
                <div class="text-label color-normal " style="position: absolute; left:10px;
                width: 48px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">ALL</div>

                <!-- Freq -->
                <div class="pair__col color-source" style="left: 48px">
                    <div class="pair-pos__num dim">7,424</div>
                    <div class="pair-pos__perc">100%</div>
                </div>
                <!-- Targets -->
            </div>
        <div id="detail_cat_end-7"></div>
    </div>

    <!-- ASSOCIATIONS -->
    <div class="pos-detail-cat-assoc-1" id="cat-assoc-CC-f7">
        <!-- no background for target in vertical mode -->
        <span class="bg-extra-column"></span>
        <div class="container-detail-assoc " id="cat-assoc-window-f7">
            <!-- CAT-CAT -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                CATEGORICAL ASSOCIATIONS<br>
                (UNCERTAINTY COEFFICIENT, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Rating_category<br>
            PROVIDES INFORMATION ON...</div>
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Installs<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Price<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Content Rating<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Type<!----></div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
            <br>
            <div class="text-large-bold" style="line-height: 104%;">THESE FEATURES<br>GIVE INFORMATION<br>
            ON Rating_category:</div>
            <hr>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Installs</div>
                    <div class="pos-assoc-row__source text-label color-source">0.08</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Price</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row " >
                    <div class="pos-assoc-row__label text-label">Content Rating</div>
                    <div class="pos-assoc-row__source text-label color-source">0.01</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Type</div>
                    <div class="pos-assoc-row__source text-label color-source">0.00</div>
                </div>
            <br>
            <!-- CAT-NUM -->
            <div class="text-small-bold color-light" style="text-align:right; line-height: 10px">
                NUMERICAL ASSOCIATIONS<br>
                (CORRELATION RATIO, 0 to 1)
            </div>
            <div class="text-large-bold" style="line-height: 104%;">Rating_category<br>
                    CORRELATION RATIO WITH...</div>
            <hr>
                <div class="assoc-row " style="font-weight: bold;">
                    <div class="pos-assoc-row__label text-label">Reviews</div>
                    <div class="pos-assoc-row__source text-label color-source">0.23</div>
                </div>
                <div class="assoc-row row-colored" >
                    <div class="pos-assoc-row__label text-label">Category</div>
                    <div class="pos-assoc-row__source text-label color-source">0.03</div>
                </div>
        </div>
    </div>
</div>
</div>
        </div>
</div>
</body>
</html>
