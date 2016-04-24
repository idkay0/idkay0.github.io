## Javascript 연습장 v1

[CodeMirror](https://github.com/codemirror/CodeMirror)를 사용해 만든 간단한 연습장입니다.


### CodeMirror 수정기록   
- 160423   
/lib/codemirror.js:1194 
```javascript
	// 2016.04.24 idkay0@gmail.com
	// function disableBrowserMagic(field) {
	//   field.setAttribute("autocorrect", "off");
	//   field.setAttribute("autocapitalize", "off");
	//   field.setAttribute("spellcheck", "false");
	// }
	function disableBrowserMagic(field) {
	 field.setAttribute("autocorrect", "none");
	 field.setAttribute("autocapitalize", "none");
	 field.setAttribute("spellcheck", "false");
	}
```