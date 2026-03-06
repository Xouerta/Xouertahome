# 📋 每日委托 D-001：打怪计数

## 委托等级：🔥 红色委托（简单）

## 📖 委托背景
你刚走出**北郡修道院**，准备开始你的冒险生涯。一位身穿破旧皮甲的卫兵拦住了你：

“年轻的冒险者，看到那些狗头人了吗？它们最近越来越猖狂了，经常偷袭我们的商队。如果你能帮我解决掉10只狗头人，我会给你相应的经验值奖励。每只狗头人价值15点经验，去试试你的身手吧！”

你握紧手中的新手剑，望向远处那些鬼鬼祟祟的狗头人——是时候开始你的第一场战斗了！

## 🎯 委托目标
计算击败10个狗头人后，总共获得多少经验值。

**基础目标：**
- 每个狗头人提供15点经验
- 击败10个狗头人
- 计算总经验值

## 💻 初始代码

### JavaScript 版本
```javascript
/**
 * 计算击败狗头人获得的总经验
 * @param {number} dogCount - 击败的狗头人数量
 * @param {number} expPerDog - 每个狗头人的经验值
 * @returns {number} 总经验值
 */
function calculateExperience(dogCount, expPerDog) {
    // 请在下面编写你的代码
    // 提示：总经验 = 狗头人数量 × 每个狗头人的经验
    
    return 0; // 修改这里的返回值
}

// 测试用例 - 运行看看你的函数是否正确
console.log("====== 测试用例 1 ======");
console.log("击败10个狗头人，每个15经验");
console.log("结果：", calculateExperience(10, 15)); // 应该输出 150

console.log("\n====== 测试用例 2 ======");
console.log("击败5个狗头人，每个20经验");
console.log("结果：", calculateExperience(5, 20));  // 应该输出 100

console.log("\n====== 测试用例 3 ======");
console.log("击败0个狗头人，每个15经验");
console.log("结果：", calculateExperience(0, 15));  // 应该输出 0
```

### Python 版本
```python
def calculate_experience(dog_count, exp_per_dog):
    """
    计算击败狗头人获得的总经验
    
    参数:
        dog_count: int - 击败的狗头人数量
        exp_per_dog: int - 每个狗头人的经验值
    
    返回:
        int - 总经验值
    """
    # 请在下面编写你的代码
    # 提示：总经验 = 狗头人数量 × 每个狗头人的经验
    
    return 0  # 修改这里的返回值

# 测试用例
print("====== 测试用例 1 ======")
print("击败10个狗头人，每个15经验")
print("结果：", calculate_experience(10, 15))  # 应该输出 150

print("\n====== 测试用例 2 ======")
print("击败5个狗头人，每个20经验")
print("结果：", calculate_experience(5, 20))   # 应该输出 100

print("\n====== 测试用例 3 ======")
print("击败0个狗头人，每个15经验")
print("结果：", calculate_experience(0, 15))   # 应该输出 0
```

### Java 版本
```java
public class Quest001 {
    
    /**
     * 计算击败狗头人获得的总经验
     * @param dogCount 击败的狗头人数量
     * @param expPerDog 每个狗头人的经验值
     * @return 总经验值
     */
    public static int calculateExperience(int dogCount, int expPerDog) {
        // 请在下面编写你的代码
        // 提示：总经验 = 狗头人数量 × 每个狗头人的经验
        
        return 0; // 修改这里的返回值
    }
    
    public static void main(String[] args) {
        System.out.println("====== 测试用例 1 ======");
        System.out.println("击败10个狗头人，每个15经验");
        System.out.println("结果：" + calculateExperience(10, 15)); // 应该输出 150
        
        System.out.println("\n====== 测试用例 2 ======");
        System.out.println("击败5个狗头人，每个20经验");
        System.out.println("结果：" + calculateExperience(5, 20));  // 应该输出 100
        
        System.out.println("\n====== 测试用例 3 ======");
        System.out.println("击败0个狗头人，每个15经验");
        System.out.println("结果：" + calculateExperience(0, 15));  // 应该输出 0
    }
}
```

### Rust 版本
```rust
fn calculate_experience(dog_count: i32, exp_per_dog: i32) -> i32 {
    // 请在下面编写你的代码
    // 提示：总经验 = 狗头人数量 × 每个狗头人的经验
    
    0 // 修改这里的返回值
}

fn main() {
    println!("====== 测试用例 1 ======");
    println!("击败10个狗头人，每个15经验");
    println!("结果：{}", calculate_experience(10, 15)); // 应该输出 150
    
    println!("\n====== 测试用例 2 ======");
    println!("击败5个狗头人，每个20经验");
    println!("结果：{}", calculate_experience(5, 20));  // 应该输出 100
    
    println!("\n====== 测试用例 3 ======");
    println!("击败0个狗头人，每个15经验");
    println!("结果：{}", calculate_experience(0, 15));  // 应该输出 0
}
```

## 🎨 进阶挑战

完成了基础任务？很好！现在试试这些进阶挑战，获得更多经验值：

### 挑战一：不同种类的狗头人 🪙（中等）
狗头人也有不同的种类！有些是普通狗头人（15经验），有些是狗头人监工（25经验），还有些是狗头人萨满（30经验）。写一个函数，接收一个狗头人数组，计算总经验。

```javascript
// 进阶挑战1的测试数据
const kobolds = [
    { type: "普通", exp: 15 },
    { type: "监工", exp: 25 },
    { type: "普通", exp: 15 },
    { type: "萨满", exp: 30 },
    { type: "监工", exp: 25 }
];

function calculateMixedExperience(kobolds) {
    // 你的代码：遍历数组，累加经验
}

console.log(calculateMixedExperience(kobolds)); // 应该输出 110
```

### 挑战二：暴击经验 💎（困难）
有时候你会打出暴击，获得双倍经验！写一个函数，输入狗头人数量、每个经验值和暴击率（0-1之间的小数），返回总经验（考虑暴击随机性）。

```javascript
function calculateWithCrit(dogCount, expPerDog, critRate) {
    // 你的代码：
    // 1. 对于每只狗头人，用Math.random()判断是否暴击
    // 2. 暴击则获得2倍经验
    // 3. 返回总经验
}

// 测试多次运行，看结果范围
for (let i = 0; i < 5; i++) {
    console.log(calculateWithCrit(10, 15, 0.3));
}
```

### 挑战三：经验加成 Buff 💎（困难）
你可能有各种经验加成 Buff：新手Buff（+10%经验）、公会Buff（+20%经验）、VIP Buff（+30%经验）。写一个函数，输入基础经验和一个Buff数组，计算最终经验。

```javascript
function calculateWithBuffs(baseExp, buffs) {
    // buffs格式: [{ name: "新手Buff", multiplier: 1.1 }, ...]
    // 你的代码：将所有乘数相乘，然后乘以基础经验
}

const buffs = [
    { name: "新手Buff", multiplier: 1.1 },
    { name: "公会Buff", multiplier: 1.2 }
];
console.log(calculateWithBuffs(150, buffs)); // 150 * 1.1 * 1.2 = 198
```

## 📝 提交格式

完成委托后，请按以下格式提交：

```markdown

## 基础委托
### 代码
```javascript
function calculateExperience(dogCount, expPerDog) {
    return dogCount * expPerDog;
}
```

### 运行结果
```
====== 测试用例 1 ======
击败10个狗头人，每个15经验
结果：150

====== 测试用例 2 ======
击败5个狗头人，每个20经验
结果：100

====== 测试用例 3 ======
击败0个狗头人，每个15经验
结果：0
```

## 💡 知识点解析

### 本次委托涉及的核心概念

| 概念 | 说明 | 示例 |
|------|------|------|
| **变量** | 存储数据的容器 | `let dogCount = 10;` |
| **数值运算** | 数学计算操作 | `*` 乘法运算符 |
| **函数** | 封装可重用代码 | `function calculate() {}` |
| **返回值** | 函数输出的结果 | `return total;` |
| **参数** | 函数接收的输入 | `(dogCount, expPerDog)` |

### 常见错误及解决

```javascript
// ❌ 错误1：忘了return
function calculateExperience(dogCount, expPerDog) {
    let total = dogCount * expPerDog;
    // 忘了return，函数返回undefined
}

// ✅ 正确写法
function calculateExperience(dogCount, expPerDog) {
    return dogCount * expPerDog;
}

// ❌ 错误2：用错了运算符
function calculateExperience(dogCount, expPerDog) {
    return dogCount + expPerDog; // 应该是乘法，写成加法
}

// ✅ 正确写法
function calculateExperience(dogCount, expPerDog) {
    return dogCount * expPerDog;
}
```

### 下一站预告
完成这个委托后，你已经准备好了迎接下一个挑战：

**D-002：背包整理** - 学习数组操作和排序算法！

---

## 🤔 思考题

1. 如果你击败了3.5只狗头人（不是整数），总经验应该怎么算？
2. 为什么计算机里整数运算和浮点数运算有时候结果不一样？
3. 如果每个狗头人给的经验值是字符串"15"而不是数字15，会发生什么？怎么处理？

---

**记住：每个大师都曾是新手中的新手，你的第一行代码就是通往传奇的第一步！**

*愿你的代码永远不报错！* 🎮
