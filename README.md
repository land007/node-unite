# node-whfmthify
Wait here for me to handle it for you

��������Ҹ�����ͳһ����

```JavaScript
const whfmthify = require('whfmthify');

var crawling = function(from, till, max) {
	return new Promise(async function(resolve, reject) {
	});
};
var reptile = function(from, till, max) {
	return new Promise(async function(resolve, reject) {
		let items = await whfmthify(crawling, from, till, max);
		resolve(items);
	});
};

```