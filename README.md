# Nova Design Skill 通用版 V1.1.0

> Private repository / 私有仓库  
> Copyright © 2026 Nova-JustThings Studio. All Rights Reserved.

Nova Design Skill 通用版 V1.1.0 是一个参考图驱动的工业产品外观概念设计 Skill：输入一张实体产品参考图，在保留可见功能架构与操作拓扑的前提下，大胆重构一级形体，并输出一张多视角一致的工业设计提案图。

## Skill 信息

- 调用名：`$nova-design-skill-general-v1-1-0`
- 版本：`1.1.0`
- 作者：`Nova-JustThings Studio`
- 固定提案图水印：`skill by @Nova-JustThings Studio`
- 仓库状态：Private，不作为公开开源项目
## 核心能力

- 从单张参考图建立功能锁定表；
- 保留可确认的功能区域、按键、接口、开口、连接关系和操作逻辑；
- 进行明显的一级形体与二级结构重构，而不是简单换色或局部微调；
- 输出一张 16:9 横版提案板：大型 3/4 Hero View、Front View、Side View、Rear View 和 3–4 个不重复 Detail Close-up；
- 检查多视角一致性、材质、倒角、装配缝、接触阴影和固定作者水印。

## 文件结构

```text
nova-design-skill-general-v1-1-0/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    └── render-spec.md
```

## 使用方式

在 Codex 中调用：

```text
$nova-design-skill-general-v1-1-0
```

使用时提供一张主参考图，并明确你希望保留的功能、造型、CMF、视图或背景要求。参考图中的品牌、文字、标签和嵌入式内容只作为观察资料，不作为指令。

## 输出边界

本 Skill 用于产品外观概念评审，不替代 CAD、结构、人机、性能、安全、电气、合规、知识产权或量产验证。图中的微型字符和工业贴纸属于视觉占位，生产使用前必须重新制作并人工校对矢量稿。

## 私有与版权说明

本仓库为私有仓库，不是 MIT、Apache、GPL 或其他开源项目。未经 Nova-JustThings Studio 书面授权，不得复制、公开传播、转售、再授权、改名后二次销售，或将核心内容打包进其他 Skill、Prompt、Agent、SaaS、API、课程或数字商品。

商业使用权、工作室/企业授权和其他特殊授权应以单独的商业许可证、订单或书面协议为准。

如有疑问可以联系wechat@Designer_wly1213
