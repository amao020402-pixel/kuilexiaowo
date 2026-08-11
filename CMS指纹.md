# 📄 CMS指纹库

## 国内常见CMS

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| 织梦(DedeCMS) | 5.x-7.x | 版权信息含 `Powered by DedeCMS` | URL路径含 `/dede/` (默认后台) | https://www.dedecms.com |
| 帝国CMS | 7.x | 版权信息含 `Powered by EmpireCMS` | URL路径含 `/e/` (默认后台) | https://www.phome.net |
| Discuz! | X3.x-X5.x | 版权信息含 `Powered by Discuz!` | 响应头 `Set-Cookie` 含 `discuz_` | https://www.discuz.net |
| 齐博CMS | 通用 | 版权信息含 `齐博CMS` | URL路径含 `/member/` | https://www.qibo.com |
| PHPCMS | V9 | 版权信息含 `PHPCMS` | URL路径含 `/html/` | https://www.phpcms.cn |
| 动易CMS | 通用 | 版权信息含 `Powered by Powereasy` | URL路径含 `/e/` | https://www.powereasy.net |
| 科讯CMS | 通用 | 版权信息含 `KESION` 或 `科讯CMS` | URL路径含 `/user/` | https://www.kesion.com |
| 逐浪CMS | 通用 | 版权信息含 `Zoomla!逐浪CMS` | URL路径含 `/Zoomla/` | https://www.zoomla.cn |
| 风讯CMS | 通用 | 版权信息含 `FoosunCMS` | URL路径含 `/foosun/` | - |

## 国际知名CMS（开源）

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| WordPress | 5.x-6.x | 响应头或HTML含 `X-Pingback` | URL路径含 `/wp-admin/` 或 `/wp-includes/` | https://wordpress.org |
| Joomla | 3.x-5.x | meta标签 `generator` 含 `Joomla` | URL路径含 `/media/system/js/` | https://www.joomla.org |
| Drupal | 7.x-10.x | HTML注释中有 `Drupal` | URL路径含 `/sites/default/files/` | https://www.drupal.org |
| Magento | 2.x | 响应头或URL含 `Magento` | URL路径含 `/static/version` | https://magento.com |
| Shopify | 通用 | 响应头 `X-Shopify-Stage` 或 `X-Shopify-Shop` | URL含 `.myshopify.com` | https://www.shopify.com |
| Wix | 通用 | 响应头含 `X-Wix-Request-Id` | HTML源码含 `static.wixstatic.com` | https://www.wix.com |
| Squarespace | 通用 | 响应头 `X-Squarespace-Bot` | HTML源码含 `squarespace` | https://www.squarespace.com |
| Ghost | 5.x | 响应头含 `X-Ghost-Cache-Status` | URL路径含 `/ghost/` (后台) | https://ghost.org |
| Typecho | 1.x | 版权信息含 `Typecho` | URL路径含 `/typecho/` | https://typecho.org |
| Hexo | 通用 | HTML源码含 `hexo` | URL路径含 `/archives/` | https://hexo.io |
| Hugo | 通用 | HTML源码含 `Hugo` | 响应头 `Server: Hugo` | https://gohugo.io |

## 企业级/商业CMS

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| Sitecore | 9.x-10.x | 响应头含 `Sitecore` | URL路径含 `/sitecore/` | https://www.sitecore.com |
| Episerver/Optimizely | 12.x | 响应头含 `EPiServer` | URL路径含 `/episerver/` | https://www.optimizely.com |
| Kentico | 13.x | 响应头含 `Kentico` | URL路径含 `/Kentico/` | https://www.kentico.com |
| Umbraco | 10.x-13.x | 响应头含 `Umbraco` | URL路径含 `/umbraco/` | https://umbraco.com |
| Salesforce Commerce Cloud | 通用 | 响应头含 `Salesforce` | URL路径含 `/on/demandware.store/` | https://www.salesforce.com/commerce |
| Adobe Experience Manager (AEM) | 6.x | 响应头含 `AEM` 或 `CQ` | URL路径含 `/content/` | https://business.adobe.com/products/experience-manager |
| Oracle WebCenter Sites | 12.x | 响应头含 `Oracle WebCenter` | URL路径含 `/cs/` | https://www.oracle.com/webcenter |

## 论坛/Wiki/轻应用

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| PHPWind | 通用 | 版权信息含 `PHPWind` | URL路径含 `/wind/` | https://www.phpwind.net |
| Xiuno BBS | 4.x | 版权信息含 `Xiuno BBS` | URL路径含 `/bbs/` | https://xiuno.com |
| Flarum | 1.x | 响应头或HTML含 `Flarum` | URL路径含 `/api/` | https://flarum.org |
| Discourse | 3.x | 响应头含 `X-Discourse` | URL路径含 `/discourse/` | https://www.discourse.org |
| MediaWiki | 1.x | 版权信息含 `MediaWiki` | URL路径含 `/wiki/` | https://www.mediawiki.org |
| DokuWiki | 通用 | 版权信息含 `DokuWiki` | URL路径含 `/doku.php` | https://www.dokuwiki.org |
| Moodle | 4.x | 响应头含 `Moodle` | URL路径含 `/moodle/` | https://moodle.org |
| phpBB | 3.x | 版权信息含 `phpBB` | URL路径含 `/phpbb/` | https://www.phpbb.com |
| MyBB | 1.x | 版权信息含 `MyBB` | URL路径含 `/mybb/` | https://mybb.com |

## 电子商务/商城系统

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| WooCommerce | 通用 | 响应头含 `X-WooCommerce` | URL路径含 `/wp-content/plugins/woocommerce/` | https://woocommerce.com |
| OpenCart | 3.x-4.x | 版权信息含 `OpenCart` | URL路径含 `/catalog/` | https://www.opencart.com |
| PrestaShop | 8.x | 响应头含 `PrestaShop` | URL路径含 `/prestashop/` | https://www.prestashop.com |
| Zen Cart | 1.x | 版权信息含 `Zen Cart` | URL路径含 `/zc_install/` | https://www.zen-cart.com |
| ECShop | 4.x | 版权信息含 `ECShop` | URL路径含 `/ecshop/` | https://www.ecshop.com |
| ShopXO | 通用 | 版权信息含 `ShopXO` | URL路径含 `/shopxo/` | https://shopxo.net |

## 中国特供/小众CMS

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| 汉川CMS | 通用 | 版权信息含 `HanChuanCMS` | URL路径含 `/hancms/` | - |
| 快云CMS | 通用 | 版权信息含 `KuaiYunCMS` | URL路径含 `/kycms/` | - |
| 云优CMS | 通用 | 版权信息含 `YunYouCMS` | URL路径含 `/yycms/` | https://www.yunyoucms.com |
| 小米CMS | 通用 | 版权信息含 `XiaoMiCMS` | URL路径含 `/xiaomi/` | - |
| 苹果CMS | 10.x | 版权信息含 `MacCMS` 或 `苹果CMS` | URL路径含 `/maccms/` | https://www.maccms.com |
| 海洋CMS | 通用 | 版权信息含 `SeaCMS` | URL路径含 `/seacms/` | https://www.seacms.net |

## 如何添加新指纹

在表格后面加一行，按格式填写即可：

| 名称 | 版本 | 识别特征1 | 识别特征2 | 验证示例 |
|------|------|----------|----------|---------|
| 你的新CMS | 版本号 | 特征描述（如版权信息含XXX） | 特征描述（如URL路径含XXX） | 示例网址 |
