# App设置

> 更新记录

<table>
    <tr>
        <th style="width:250px;">日期</th>
        <th>更新内容</th>
    </tr>
    <tr>
        <td>2018-06-04 10:53:38</td>
        <td>生成时间</td>
    </tr>
</table>

> 字段

<table>
    <tr>
        <th style="width:500px;">名称</th>
        <th style="width:300px;">路径</th>
        <th style="width:100px;">类型</th>
        <th>可选值</th>
    </tr>
    <tr>
        <td>积分模块开关</td>
        <td>module.score.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>积分模块: 消费1元积分数</td>
        <td>module.score.inUnit</td>
        <td>int</td>
        <td>消费1元积分数, 默认: 1</td>
    </tr>
    <tr>
        <td>积分模块: 抵扣1元金额所需积分数</td>
        <td>module.score.outUnit</td>
        <td>int</td>
        <td>抵扣1元金额所需积分数</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>预储值模块开关</td>
        <td>module.deposit.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>服务卡模块开关</td>
        <td>module.serviceCard.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>微信模块开关</td>
        <td>module.wechat.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>短信模块开关</td>
        <td>module.sms.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>通知模块开关</td>
        <td>module.notice.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 验光单通知开关</td>
        <td>module.notice.optometry.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 验光单通知方式</td>
        <td>module.notice.optometry.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 下单通知开关</td>
        <td>module.notice.orderCreate.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 下单通知方式</td>
        <td>module.notice.orderCreate.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 储值卡使用通知开关</td>
        <td>module.notice.depositUse.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 储值卡使用通知方式</td>
        <td>module.notice.depositUse.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 积分使用通知开关</td>
        <td>module.notice.scoreUse.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 积分使用通知方式</td>
        <td>module.notice.scoreUse.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 服务卡使用通知开关</td>
        <td>module.notice.serviceCardUse.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 服务卡使用通知方式</td>
        <td>module.notice.serviceCardUse.enabled</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 取货通知开关</td>
        <td>module.notice.orderReady.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 取货通知方式</td>
        <td>module.notice.orderReady.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 订单完成通知开关</td>
        <td>module.notice.orderComplete.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 订单完成通知方式</td>
        <td>module.notice.orderComplete.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 验光筛查通知开关</td>
        <td>module.notice.optometryReview.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 验光筛查通知方式</td>
        <td>module.notice.optometryReview.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 框架换镜通知开关</td>
        <td>module.notice.glassExpired.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 框架换镜通知方式</td>
        <td>module.notice.glassExpired.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 隐形换镜通知开关</td>
        <td>module.notice.contactLensExpired.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 隐形换镜通知方式</td>
        <td>module.notice.contactLensExpired.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>会员等级</td>
        <td>customer.levelList</td>
        <td>array</td>
        <td>按消费金额: 范例: [{"money":0, "level":"普通会员", "benefit": "每年享受一次免费眼健康全面检查服务"}, {"money":500, "level":"铜牌会员", "benefit": "每年享受两次免费眼健康全面检查服务"}, {"money":1000, "level":"银牌会员", "benefit": "每年享受三次免费眼健康全面检查服务"}, {"money":3000, "level":"金牌会员", "benefit": "每年享受四次免费眼健康全面检查服务"}, {"money":5000, "level":"白金会员", "benefit": "每年享受五次免费眼健康全面检查服务"}, {"money":10000, "level":"钻石会员", "benefit": "每年享受六次免费眼健康全面检查服务"}, {"money":30000, "level":"黑卡会员", "benefit": "每年享受七次免费眼健康全面检查服务"}]</td>
    </tr>
    <tr>
        <td>顾客画像</td>
        <td>customer.tagList</td>
        <td>array</td>
        <td>默认值: 老主顾,新顾客</td>
    </tr>
</table>

## 查看APP设置

```
GET /admin/app-setting/get-by-app-id
```

> 参数, appId

## 更新APP设置

```
POST /admin/app-setting/update
```

> 参数

<table>
    <tr>
        <th style="width:150px;">属性名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:60px;">必填</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>appId</td>
        <td>int</td>
        <td>是</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>setting</td>
        <td>map</td>
        <td>-</td>
        <td>设置项</td>
        <td>-</td>
    </tr>
</table>