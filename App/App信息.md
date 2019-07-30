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
        <td>setting</td>
        <td>map</td>
        <td>-</td>
        <td>设置项</td>
        <td>见下表</td>
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

### 设置项
<table>
    <tr>
        <th style="width:150px;">名称</th>
        <th style="width:200px;">路径</th>
        <th style="width:200px;">类型</th>
        <th>可选值</th>
    </tr>
    <tr>
        <td>模块</td>
        <td>/module</td>
        <td>leaf</td>
        <td>-</td>
    </tr>
    <tr>
        <td>积分模块</td>
        <td>/module/score</td>
        <td>leaf</td>
        <td>-</td>
    </tr>
    <tr>
        <td>积分模块开关</td>
        <td>/module/score/enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>积分模块设置项</td>
        <td>/module/score/setting</td>
        <td>map</td>
        <td>积分模块设置项</td>
    </tr>
    <tr>
        <td>预储值模块</td>
        <td>/module/deposit</td>
        <td>leaf</td>
        <td>-</td>
    </tr>
    <tr>
        <td>预储值模块开关</td>
        <td>/module/deposit/enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>预储值模块设置项</td>
        <td>/module/deposit/setting</td>
        <td>map</td>
        <td>预储值模块设置项</td>
    </tr>
</table>

## 列表

```
GET /admin/app
```