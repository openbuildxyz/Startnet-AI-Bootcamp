## 项目名称：AI Red Light, Green Light

此游戏灵感来源于鱿鱼游戏123木头人。

- 演示视频: [Video Link](https://cdn.shopify.com/videos/c/o/v/f3da21ddc42c40d39243f4ba263d8f8d.mp4)
- 项目代码: [Github Link](https://github.com/0xdiymax/ai-red-light-green-light)
## 游戏玩法

玩家通过掷骰子在赛道上前进。一个 AI 预言机会尝试预测玩家的掷骰结果。

- 如果 AI 预测正确（红灯！），玩家将受到惩罚并返回起点。
- 如果 AI 预测错误（绿灯！），玩家将向前移动。

游戏的目标是成功到达赛道终点，赢得奖池中的奖品。

## 费用与奖池

💰 每次移动都需要支付少量 STRK 作为费用。一部分费用会进入当前的奖池，其余部分用于资助未来的奖品。当有玩家赢得奖品后，新的奖品将从合约的余额中设置。

## AI 实现

🤖 在此版本中，AI 的预测由链上的模拟预言机合约生成。未来的版本可能会集成更复杂的链下 AI。
