# EntityType (enum)
EntityTypeは、対象となるエンティティを表します。<br>
※リクエスト時はEntityTypeで定義されている値をString型で指定します。<br>
※レスポンスの値はenumとして返却されます。

### Service
+ [CampaignExportService](../../services/CampaignExportService.md)

### Namespace
[CampaignExportService#Namespace](../../services/CampaignExportService.md#namespace)

<table>
 <tr>
  <th>Enumeration </th>
  <th>Type</th>
  <th>Description</th>
 <tr>
  <td>ACCOUNT</td>
  <td>xsd:string</td>
  <td>アカウントです。</td>
 </tr>
 <tr>
  <td>CAMPAIGN</td>
  <td>xsd:string</td>
  <td>キャンペーンです。</td>
 </tr>
 <tr>
  <td>NEGATIVE_CAMPAIGN_CRITERION</td>
  <td>xsd:string</td>
  <td>対象外キーワードです。（キャンペーン）</td>
 </tr>
 <tr>
  <td>CAMPAIGN_TARGET</td>
  <td>xsd:string</td>
  <td>キャンペーンのターゲティング設定です。</td>
 </tr>
 <tr>
  <td>AD_GROUP</td>
  <td>xsd:string</td>
  <td>広告グループです。</td>
 </tr>
 <tr>
  <td>BIDDABLE_AD_GROUP_CRITERION</td>
  <td>xsd:string</td>
  <td>入札キーワードです。</td>
 </tr>
 <tr>
  <td>NEGATIVE_AD_GROUP_CRITERION</td>
  <td>xsd:string</td>
  <td>対象外キーワードです。（広告グループ）</td>
 </tr>
 <tr>
  <td>AD</td>
  <td>xsd:string</td>
  <td>広告です。</td>
 </tr>
 <tr>
  <td>ALL</td>
  <td>xsd:string</td>
  <td>すべてです。</td>
 </tr>
 <tr>
  <td>FEED_ITEM</td>
  <td>xsd:string</td>
  <td>FeedItemの種類です。</td>
 </tr>
 <tr>
  <td>CAMPAIGN_FEED</td>
  <td>xsd:string</td>
  <td>FeedItemのキャンペーン情報です。</td>
 </tr>
 <tr>
  <td>AD_GROUP_FEED</td>
  <td>xsd:string</td>
  <td>FeedItemの広告グループ情報です。</td>
 </tr>
 <tr>
  <td>BIDDING_STRATEGY</td>
  <td>xsd:string</td>
  <td>自動入札設定です。</td>
 </tr>
 <tr>
  <td>FEED_FOLDER</td>
  <td>xsd:string</td>
  <td>Feedフォルダーです。</td>
 </tr>
 <tr>
  <td>NEGATIVE_CAMPAIGN_TARGET_LIST</td>
  <td>xsd:string</td>
  <td>除外キャンペーンユーザリストです。</td>
 </tr>
 <tr>
  <td>AD_GROUP_TARGET_LIST</td>
  <td>xsd:string</td>
  <td>広告グループユーザリストです。</td>
 </tr>
 <tr>
  <td>TARGET_LIST</td>
  <td>xsd:string</td>
  <td>ターゲットリストです。</td>
 </tr>
</table>

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
