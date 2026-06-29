import streamlit as st

st.set_page_config(page_title="Nexus V1 Demo", layout="centered")

st.title("🧠 Nexus V1 — AI Consensus Engine")
st.write("Single Scenario Demo: 如何拥有腹肌")

user_input = st.text_input("输入你的问题", "我想拥有腹肌")

if st.button("Analyze"):

    st.subheader("🔍 Step 1：AI分析中")
    st.write("""
AI正在调用多个模型：
✔ GPT  
✔ Claude  
✔ Gemini  

正在进行交叉验证...
""")

    st.subheader("🤖 Step 2：多AI输出")

    st.write("**GPT：** 热量缺口 + 力量训练 + 有氧")
    st.write("**Claude：** 饮食控制 + 核心训练 + 睡眠优化")
    st.write("**Gemini：** 有氧运动 + 低脂饮食 + 核心训练")

    st.subheader("📊 Step 3：共识分析")

    st.write("✔ 共识内容：")
    st.write([
        "热量缺口",
        "核心训练",
        "饮食控制"
    ])

    st.write("⚠ 分歧内容：")
    st.write([
        "低碳饮食是否必要",
        "有氧 vs 力量优先级"
    ])

    st.subheader("⚖ Step 4：可信度判断")

    st.write("🟢 高可信度")
    st.write(["热量缺口", "核心训练"])

    st.write("🟡 中可信度")
    st.write(["低碳饮食"])

    st.write("🔴 低可信度")
    st.write(["局部减脂"])

    st.subheader("📌 Step 5：Nexus结论")

    st.success("""
🎯 最有效路径：

1. 热量缺口（核心因素）
2. 力量训练 + 核心训练
3. 控制饮食结构 + 规律训练

⚠ 争议点：
- 低碳饮食不是必须条件
- 有氧 vs 力量取决于体脂

❌ 错误观点：
- 局部减脂不存在生理依据
""")