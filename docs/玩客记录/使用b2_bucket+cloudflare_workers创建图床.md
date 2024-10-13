# 使用`B2_Bucket`+`Cloudflare_Worker`创建图床

## 简述

在上个[Rclone与b2_bucket结合的文章](/docs/玩客记录/使用rclone+b2_bucket进行文件备份.md)中介绍了B储存的几大优势，所以我们这次仍然选择B2作为储存

并且我们发现，Cloudflare与B2之间的流量是完全免费的，且Cloudflare的Workers免费用户每天能有100,000次的请求，这足以支撑一个小型博客+知识库的图片需求

这篇文章就主要讲述了如何将两者结合，构建一个个人图床。


