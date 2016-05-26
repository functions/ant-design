---
order: 3
title:
  zh-CN: 更灵活的内容展示
  en-US: More flexible content
---

## zh-CN

可以调整默认边距，设定宽度。

## en-US

An advanced usage of a card, adjusting the width and the default margins.

````jsx
import { Card } from 'antd';

ReactDOM.render(
  <Card style={{ width: 240 }} bodyStyle={{ padding: 0 }}>
    <div className="custom-image">
      <img alt="example" width="100%" src="https://os.alipayobjects.com/rmsportal/QBnOOoLaAfKPirc.png" />
    </div>
    <div className="custom-card">
      <h3>Europe Street beat</h3>
      <p>www.instagram.com</p>
    </div>
  </Card>
, mountNode);
````

````css
.custom-image img {
  display: block;
}
.custom-card {
  padding: 10px 16px;
}
.custom-card p {
  color: #999;
}
````
