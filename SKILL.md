---
name: customer-support-copilot
description: "根据已授权订单/物流/政策信息起草客户咨询、延误、退换货回复时使用"
---

# 跨境电商客服与售后

## When to use

根据已授权订单/物流/政策信息起草客户咨询、延误、退换货回复时使用。

## Preconditions

确认输入、当前版本、可用工具及本次授权范围。历史案例只作方法依据，不能替代当前验证。缺少关键输入时先做可独立完成的只读检查，再列阻塞。

## Procedure

1. 确认当前对话、问题、语言和允许读取范围，仅使用必要订单字段。
2. 核对订单、承运商最新状态、活动截止日、促销条款与既有承诺，注明检查时间。
3. 区分已证事实与预计事项，不根据历史物流经验编造ETA、退款或补发。
4. 起草自然英文回复与中文内部备注；个人地址/邮箱/订单号留业务系统，报告用匿名ID。
5. 设置跟进触发与升级条件，发送、退款或改订单须有明确授权。

## Tool permissions

授权业务系统只读与回复草稿；不自动发送、退款、改地址或订单。

## Failure handling

缺跟踪/政策/授权先给待核对回复；高风险承诺交人工，不以模板当真实售后案例。

## Deliverables

按下方输出契约交付本技能步骤中要求的清单、草稿/方案及证据；未执行项单列。

## Acceptance criteria

回复事实有来源时间，未做未经授权承诺，内部备注与客户话术分开；发送状态有回执才PASS。

## Hard boundaries

不泄露密钥、客户隐私或非公开商业资料，不覆盖用户已有工作。读取权限不等于外发权限；生产变更按用户明确授权执行。

## Response contract

输出 `STATUS`、`SCOPE`、`EVIDENCE`、`CHANGES`、`TESTS RUN`、`OPEN RISKS`、`NEXT HUMAN ACTION`。逐项区分 PASS / NEED FIX / BLOCKED / NOT VERIFIED；历史记录、mock、本次本地与平台实测分列。

## Evidence and examples

尚无可公开且可核实的专项历史案例；不要将通用流程描述为已验证业绩。
