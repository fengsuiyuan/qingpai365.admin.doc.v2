# App信息

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
        <th style="width:150px;">属性名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:60px;">必填</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>id</td>
        <td>string</td>
        <td>-</td>
        <td></td>
        <td>-</td>
    </tr>
    <tr>
        <td>serverId</td>
        <td>int</td>
        <td>-</td>
        <td>服务器ID</td>
        <td>-</td>
    </tr>
    <tr>
        <td>clientId</td>
        <td>int</td>
        <td>-</td>
        <td>客户ID</td>
        <td>-</td>
    </tr>
    <tr>
        <td>userId</td>
        <td>int</td>
        <td>是</td>
        <td>创建人userId</td>
        <td>-</td>
    </tr>
    <tr>
        <td>deviceCount</td>
        <td>int</td>
        <td>是</td>
        <td>设备数量</td>
        <td>-</td>
    </tr>
    <tr>
        <td>shopCount</td>
        <td>int</td>
        <td>是</td>
        <td>门店数量</td>
        <td>-</td>
    </tr>
    <tr>
        <td>smsCount</td>
        <td>int</td>
        <td>是</td>
        <td>短信数量</td>
        <td>-</td>
    </tr>
    <tr>
        <td>scoreModule</td>
        <td>int</td>
        <td>是</td>
        <td>是否开启积分模块</td>
        <td>-</td>
    </tr>
    <tr>
        <td>scoreModuleData</td>
        <td>object</td>
        <td>是</td>
        <td>积分模块设置</td>
        <td>保存的json序列化数据, 具体key用到的时候在这里详细写明</td>
    </tr>
    <tr>
        <td>couponModule</td>
        <td>int</td>
        <td>是</td>
        <td>是否开启优惠券模块</td>
        <td>-</td>
    </tr>
    <tr>
        <td>couponModuleData</td>
        <td>object</td>
        <td>是</td>
        <td>优惠券模块设置</td>
        <td>保存的json序列化数据, 具体key用到的时候在这里详细写明</td>
    </tr>
    <tr>
        <td>depositModule</td>
        <td>int</td>
        <td>是</td>
        <td>是否开启预储值模块</td>
        <td>-</td>
    </tr>
    <tr>
        <td>depositModuleData</td>
        <td>object</td>
        <td>是</td>
        <td>预储值模块设置</td>
        <td>保存的json序列化数据, 具体key用到的时候在这里详细写明</td>
    </tr>
    <tr>
        <td>wechatModule</td>
        <td>int</td>
        <td>是</td>
        <td>是否开启微信模块</td>
        <td>-</td>
    </tr>
    <tr>
        <td>wechatModuleData</td>
        <td>object</td>
        <td>是</td>
        <td>微信模块设置</td>
        <td>保存的json序列化数据, 具体key用到的时候在这里详细写明</td>
    </tr>
    <tr>
        <td>status</td>
        <td>int</td>
        <td>-</td>
        <td>状态</td>
        <td>100:正常 0:禁用</td>
    </tr>    
    <tr>
        <td>createdAt</td>
        <td>int</td>
        <td>-</td>
        <td>创建时间</td>
        <td>-</td>
    </tr>
</table>


## 列表

```
GET /admin/app
```