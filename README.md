# 🌐 白羊星机场 测评报告
> 自动化测试时间：2026-11-19T12:37:30　|　协议：anytls / shadowsocks（SS-Obs）
> **订阅实际节点：50 个，本次抽样测试：12 个代表节点**　|　**综合评分：65/100（良好）**

---

## 🏢 服务商简介
白羊星机场（官网 home.baiyangxing.com）是一家网络加速服务商，采用 SS-Obs / anytls 协议，提供全球 60+ 国家/地区、50+ 节点，分「Connect（常规）」和「流媒体」两类线路，主打多地 BGP 跨境专线，官方宣称支持 Netflix/Hulu/Hbo/Disney+/ChatGPT 等流媒体。

| 项目 | 说明 |
|------|------|
| 协议 | SS-Obs / anytls |
| 线路类型 | 多地 BGP 跨境专线出国 |
| 覆盖地区 | 全球 60+ 国家/地区，50+ 节点 |
| 节点分类 | Connect（常规）+ 流媒体专线 |
| 节点数量 | 订阅实际 50 个节点，本次抽样测试 12 个代表节点 |
| 设备支持 | 5~20 台（按套餐） |
| 流媒体 | 官方宣称支持 Netflix/Hulu/Hbo/Disney+/ChatGPT |

> ⚠️ 以上含服务商官方宣传信息；Netflix 解锁因节点地区而异（香港/日本/美国/英国节点多可解锁，台湾节点多为本地区），请以本报告实测结果为准。

---

## 💰 套餐价格

| 套餐 | 价格 | 流量 | 说明 |
|------|------|------|------|
| 基础配置 | ¥12/月 | 100 GB/月 | 5 台设备，新用户推荐 |
| 中级配置 | ¥25/月 | 300 GB/月 | 8 台设备 |
| 高级配置 | ¥48/月 | 800 GB/月 | 10 台设备 |
| 轻量年付 | ¥89/年 | 50 GB/月 | 3 台设备，约 ¥7.4/月 |
| 白羊专属配置 | ¥188/年 | 230 GB/月 | 10 台设备，约 ¥15.7/月 |
| 精英流量包 | ¥88 一次性 | 100 GB | 无重置期限，用完即止，8 台设备 |
| 宗师流量包 | ¥155 一次性 | 300 GB | 无重置期限，10 台设备（当前套餐） |
| 传家级流量包 | ¥388 一次性 | 3000 GB | 无重置期限，20 台设备 |

🎟️ **优惠码：`N888`**

🔗 注册链接：https://home.baiyangxing.com/#/register?code=bkAdlVQX

---

## 📊 核心数据

| 指标 | 结果 |
|------|------|
| 订阅实际节点总数 | 50 个 |
| 本次测试节点数 | 12 个（抽样代表节点）|
| 节点可用率 | 12/12（100%）|
| 平均下载速度 | 85.1 Mbps（最高 321.8 / 最低 5.3）|
| 真实 CDN 下载 | 平均 27.0 Mbps（Cloudflare 10MB）|
| DNS 隧道正常 | 11/12 |
| Netflix 解锁 | 8/12 |
| YouTube 解锁 | 12/12 |
| Disney+ 解锁 | 12/12 |

### 一句话结论

这是**代理型机场服务**（不是完整 VPN）。12 个测试节点中 12 个连通；平均下载 85.1 Mbps，真实 CDN 下载平均 27.0 Mbps。YouTube 12/12、Netflix 8/12、Disney+ 12/12。香港节点速度最快。整体适合日常浏览和流媒体，Netflix 解锁以实测为准。

---

## 🌍 分地区表现

| 地区 | 节点数 | 平均下载 | 最高下载 | 真实 CDN | 服务器延迟 | 评级 |
|------|:---:|:---:|:---:|:---:|:---:|:---:|
| 台湾 | 2 | 23.5 Mbps | 47.0 Mbps | 47.0 Mbps | 106ms | 🟠 较慢 |
| 新加坡 | 2 | 15.4 Mbps | 17.0 Mbps | 15.4 Mbps | 94ms | 🟠 较慢 |
| 日本 | 2 | 17.5 Mbps | 29.7 Mbps | 17.5 Mbps | 92ms | 🟠 较慢 |
| 美国 | 2 | 28.2 Mbps | 30.8 Mbps | 28.2 Mbps | 108ms | 🟠 较慢 |
| 英国 | 2 | 168.3 Mbps | 321.8 Mbps | 13.5 Mbps | 87ms | 🟢 快 |
| 香港 | 2 | 215.1 Mbps | 307.9 Mbps | 50.2 Mbps | 108ms | 🟢 快 |

---

## 🎬 流媒体解锁

| 平台 | 结果 |
|------|------|
| YouTube | 12/12 |
| Netflix | 8/12 |
| Disney+ | 12/12 |

> 📌 Netflix 判定依据：影片页 `metaData.isAvailable` 字段（配合出口地区）。Netflix 页面内置的 "unblocker/proxy" 提示文案是所有页面都带的通用文本，不作为判据；早期版本据此误判为「全节点未解锁」，本次已修正。Netflix 解锁与出口节点地区相关，港/日/美/英等地区节点通常可解锁。

---

## 🔒 安全与 DNS

- ✅ Google DNS-over-HTTPS 通过代理正常：11/12
- ✅ ipleak.net 检测 IP 与出口 IP 一致性已验证
- ✅ bash.ws DNS 泄漏测试：DNS 服务器位于对应地区

**结论**：只要应用正确配置代理，DNS 就不会泄漏；未走代理的系统级应用仍使用本地 DNS。

---

## ✅ 优点 / ❌ 缺点

**优点**

- 节点按地区/流媒体分类清晰，便于选择
- 英国节点速度突出（最高 322 Mbps）
- YouTube、Disney+ 解锁率较高
- 套餐选择丰富（月付/年付/不限时流量包）
- 年付套餐单价低（¥89/年起）

**缺点**

- Netflix 解锁因节点地区而异（台湾节点多仅解锁本地区）
- 整体平均速度偏低（78 Mbps）
- 日本、新加坡部分流媒体节点较慢
- 不支持新疆地区
- 是代理不是完整 VPN，系统级流量不受保护

---

## 📋 详细测试数据

| 节点 | 协议 | 出口地区 | 下载 | 上传 | CDN 下载 | 服务器 Ping | DNS | YT | NF | DS |
|------|------|---------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 台湾｜Connect A | anytls | Taiwan / Taipei | 47.0 Mbps | — Mbps | 47.0 Mbps | 108ms | ✅ | ✅ | ❌ | ✅ |
| 台湾｜流媒体 A | ss | Taiwan / Taipei | — Mbps | — Mbps | — Mbps | 104ms | ⚠️ | ✅ | ❌ | ✅ |
| 新加坡｜流媒体 A | ss | Singapore / Singapore | 13.86 Mbps | — Mbps | 13.86 Mbps | 95ms | ✅ | ✅ | ❌ | ✅ |
| 新加坡｜流媒体 B | ss | Singapore / Singapore | 16.97 Mbps | — Mbps | 16.97 Mbps | 94ms | ✅ | ✅ | ❌ | ✅ |
| 日本｜流媒体 A | ss | Japan / Tokyo | 5.3 Mbps | — Mbps | 5.3 Mbps | 90ms | ✅ | ✅ | ✅ | ✅ |
| 日本｜流媒体 B | ss | Japan / Tokyo | 29.73 Mbps | — Mbps | 29.73 Mbps | 94ms | ✅ | ✅ | ✅ | ✅ |
| 美国｜Connect A | anytls | United States / Los Angeles (Downtown Los Angeles) | 25.58 Mbps | — Mbps | 25.58 Mbps | 108ms | ⚠️ | ✅ | ✅ | ✅ |
| 美国｜Connect C | anytls | United States / Los Angeles | 30.76 Mbps | — Mbps | 30.76 Mbps | 108ms | ✅ | ✅ | ✅ | ✅ |
| 英国｜流媒体 A | ss | United Kingdom / Canary Wharf | 321.84 Mbps | 113.83 Mbps | 12.24 Mbps | — | ✅ | ✅ | ✅ | ✅ |
| 英国｜流媒体 B | ss | United Kingdom / Canary Wharf | 14.72 Mbps | — Mbps | 14.72 Mbps | 87ms | ✅ | ✅ | ✅ | ✅ |
| 香港｜Connect A | anytls | Hong Kong / Hong Kong | 307.85 Mbps | 270.76 Mbps | 51.48 Mbps | 108ms | ✅ | ✅ | ✅ | ✅ |
| 香港｜Connect E | anytls | Hong Kong / Hong Kong | 122.31 Mbps | 117.68 Mbps | 48.94 Mbps | 108ms | ✅ | ✅ | ✅ | ✅ |

---

## 🎯 购买建议

<b>推荐节点</b>：英国流媒体 A（322 Mbps）、香港 Connect A（308 Mbps）速度最佳。<br><b>性价比</b>：轻量年付 ¥89/年（约 ¥7.4/月）适合轻度用户；白羊专属 ¥188/年流量更充裕。<br><b>优惠码</b>：<code>N888</code>，注册链接见上方。<br><b>适合</b>：流媒体观看、多地区切换。Netflix 推荐香港/日本/美国/英国节点；追求极致速度可选英国节点。

---

## 🛠️ 测试方法

使用 sing-box 1.14.4 + Python 自动化脚本，对每个节点执行：

1. 启动代理，访问 ip.sb 验证出口 IP 与地理位置
2. 本地 ping 代理服务器测延迟
3. Speedtest CLI 测下载/上传
4. Cloudflare CDN 下载 10MB 文件（真实速度）
5. Google DoH + ipleak.net + bash.ws DNS 检测
6. Netflix / YouTube / Disney+ 解锁测试

> 注：Speedtest 依赖服务器选择，波动较大；Cloudflare 下载更贴近真实体验。结果受当前网络环境影响，仅供参考。
