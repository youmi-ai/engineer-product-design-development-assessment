代码实现题目:
1. (客服聊天界面) 实现一个客服聊天界面的React Native组件,包含消息列表、输入框和常用快捷回复。消息列表应该支持文本、图片、文件等类型,并能够显示时间戳。输入框应该支持文本输入、表情选择和图片/文件上传。
2. (保险产品卡片) 实现一个保险产品卡片的React Native组件,用于在聊天界面中展示保险产品的关键信息,如保险名称、保障范围、保费等。卡片应该支持折叠和展开,以及点击跳转到详情页面。
3. (算法题)实现一个函数,用于在客户聊天记录中搜索包含指定关键词的消息。聊天记录以字符串数组的形式给出,每个元素代表一条消息。函数应该返回所有包含关键词的消息在原数组中的下标。请不要直接使用正则表达式,而是尝试使用其他字符串搜索算法。并分析时间和空间复杂度
```javascript
const messages = [
  "Hello, how can I help you today?",
  "I'm interested in buying a health insurance plan.",
  "Great! We offer several health insurance options.",
  "Could you provide more details about your available plans?",
  "Sure, we have basic, standard, and premium health insurance plans.",
];

function searchMessages(messages, keyword) {
  // 实现代码,不使用正则表达式
}

console.log(searchMessages(messages, "health")); // 输出 [2, 4]
console.log(searchMessages(messages, "insurance")); // 输出 [1, 2, 4]
```
   

产品设计题目:
1. (保险方案推荐) 设计一个基于客户信息和需求的保险方案推荐功能,在客服聊天过程中自动提供个性化的保险产品组合。请考虑如何收集和分析客户信息,以及如何在聊天界面中自然地展示推荐结果。
2. (财务规划工具) 设计一个嵌入式的财务规划工具,供客户在聊天界面中自助完成财务规划。工具应该引导客户输入收入、支出、投资等信息,并生成个性化的财务规划方案。请提供工具的交互流程和界面草图。
3. (经纪人工作台) 设计一个 CRM 系统的经纪人工作台界面,用于管理和跟进客服聊天系统中的潜在客户。工作台应该展示客户的基本信息、聊天记录、跟进状态等,并提供便捷的跟进操作。请考虑经纪人的日常工作流程,提供界面草图或原型。
