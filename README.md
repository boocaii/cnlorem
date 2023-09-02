# cnlorem

cnlorem 是一个随机生成中文段落（包含文字和标点）的 Javascript/Typescript 库

## Installation
```bash
npm i --save-dev cnlorem
```

## Usage

```ts
import cnlorem from 'cnlorem'

console.log(cnlorem(50))
// Output: 着打相听里平很影命美终。眼把正么斯回条过身位活水意一位告回队大片间，儿看住里口处家成，两同风流民马稜她和和。

console.log(cnlorem({n: 50, en: 3}))
// Output: 出心此然长无 dolor 该接将，认不那中行约经身死她者身方决头无论此此只着之 culpa，其望然亲同后。此经用独到 eu 内，文识次信量神都。
```

## TODO

- [x] 支持生成中英混排文本


## References
常用字来源：[http://www.tidewaterchineseschool.org/wp-content/uploads/2015/02/国家出版局抽样统计最常用的-1000-个汉字.pdf](http://www.tidewaterchineseschool.org/wp-content/uploads/2015/02/%E5%9B%BD%E5%AE%B6%E5%87%BA%E7%89%88%E5%B1%80%E6%8A%BD%E6%A0%B7%E7%BB%9F%E8%AE%A1%E6%9C%80%E5%B8%B8%E7%94%A8%E7%9A%84-1000-%E4%B8%AA%E6%B1%89%E5%AD%97.pdf)