# 📋 每日委托 D-002：背包整理

## 委托等级：🔥 红色委托（简单）

## 📖 委托背景
你刚刚击败了狗头人，从它们身上搜刮了一些战利品。现在背包里一片混乱：`['生锈的剑', '魔法卷轴', '治疗药水', '符文布', '铜币']`。作为一名优秀的冒险者，你需要把背包整理得井井有条，这样在战斗中才能快速找到需要的物品。

旅店老板告诉你：“整理背包是每个冒险者的基本功！按名称排序是最简单的方式，这样你一眼就能找到想要的东西。”

## 🎯 委托目标
写一个函数，将输入的物品数组按名称排序（按拼音/字母顺序）。

**基础目标：**
- 输入一个字符串数组（物品名称）
- 返回按名称排序后的新数组
- 不能修改原数组（保持纯函数）

## 💻 初始代码

### JavaScript 版本
```javascript
/**
 * 整理背包物品，按名称排序
 * @param {string[]} items - 背包物品数组
 * @returns {string[]} 排序后的新数组
 */
function sortItems(items) {
    // 请在下面编写你的代码
    // 提示：可以使用数组的 sort() 方法
    // 注意：不能直接修改原数组
    
    return []; // 修改这里的返回值
}

// 测试用例
console.log("====== 测试用例 1 ======");
const backpack1 = ['生锈的剑', '魔法卷轴', '治疗药水', '符文布', '铜币'];
console.log("原背包:", backpack1);
console.log("排序后:", sortItems(backpack1));
console.log("原背包是否改变:", backpack1); // 应该和原来一样

console.log("\n====== 测试用例 2 ======");
const backpack2 = ['苹果', '香蕉', '橘子', '葡萄'];
console.log("原背包:", backpack2);
console.log("排序后:", sortItems(backpack2));

console.log("\n====== 测试用例 3 ======");
const backpack3 = ['匕首', '盾牌', '长剑', '法杖', '弓箭'];
console.log("原背包:", backpack3);
console.log("排序后:", sortItems(backpack3));
```

### Python 版本
```python
def sort_items(items):
    """
    整理背包物品，按名称排序
    
    参数:
        items: list - 背包物品列表
    
    返回:
        list - 排序后的新列表
    """
    # 请在下面编写你的代码
    # 提示：可以使用 sorted() 函数
    # 注意：不能直接修改原列表
    
    return []  # 修改这里的返回值

# 测试用例
print("====== 测试用例 1 ======")
backpack1 = ['生锈的剑', '魔法卷轴', '治疗药水', '符文布', '铜币']
print("原背包:", backpack1)
print("排序后:", sort_items(backpack1))
print("原背包是否改变:", backpack1)  # 应该和原来一样

print("\n====== 测试用例 2 ======")
backpack2 = ['苹果', '香蕉', '橘子', '葡萄']
print("原背包:", backpack2)
print("排序后:", sort_items(backpack2))

print("\n====== 测试用例 3 ======")
backpack3 = ['匕首', '盾牌', '长剑', '法杖', '弓箭']
print("原背包:", backpack3)
print("排序后:", sort_items(backpack3))
```

### Java 版本
```java
import java.util.Arrays;
import java.util.ArrayList;
import java.util.List;
import java.util.Collections;

public class Quest002 {
    
    /**
     * 整理背包物品，按名称排序
     * @param items 背包物品数组
     * @return 排序后的新数组
     */
    public static String[] sortItems(String[] items) {
        // 请在下面编写你的代码
        // 提示：可以先复制数组，然后使用 Arrays.sort()
        // 注意：不能直接修改原数组
        
        return new String[0]; // 修改这里的返回值
    }
    
    public static void main(String[] args) {
        System.out.println("====== 测试用例 1 ======");
        String[] backpack1 = {"生锈的剑", "魔法卷轴", "治疗药水", "符文布", "铜币"};
        System.out.println("原背包: " + Arrays.toString(backpack1));
        System.out.println("排序后: " + Arrays.toString(sortItems(backpack1)));
        System.out.println("原背包是否改变: " + Arrays.toString(backpack1));
        
        System.out.println("\n====== 测试用例 2 ======");
        String[] backpack2 = {"苹果", "香蕉", "橘子", "葡萄"};
        System.out.println("原背包: " + Arrays.toString(backpack2));
        System.out.println("排序后: " + Arrays.toString(sortItems(backpack2)));
        
        System.out.println("\n====== 测试用例 3 ======");
        String[] backpack3 = {"匕首", "盾牌", "长剑", "法杖", "弓箭"};
        System.out.println("原背包: " + Arrays.toString(backpack3));
        System.out.println("排序后: " + Arrays.toString(sortItems(backpack3)));
    }
}
```

### Rust 版本
```rust
fn sort_items(items: &[&str]) -> Vec<String> {
    // 请在下面编写你的代码
    // 提示：可以创建新 Vec，然后排序
    // 注意：不能直接修改原切片
    
    vec![] // 修改这里的返回值
}

fn main() {
    println!("====== 测试用例 1 ======");
    let backpack1 = vec!["生锈的剑", "魔法卷轴", "治疗药水", "符文布", "铜币"];
    println!("原背包: {:?}", backpack1);
    println!("排序后: {:?}", sort_items(&backpack1));
    println!("原背包是否改变: {:?}", backpack1);
    
    println!("\n====== 测试用例 2 ======");
    let backpack2 = vec!["苹果", "香蕉", "橘子", "葡萄"];
    println!("原背包: {:?}", backpack2);
    println!("排序后: {:?}", sort_items(&backpack2));
    
    println!("\n====== 测试用例 3 ======");
    let backpack3 = vec!["匕首", "盾牌", "长剑", "法杖", "弓箭"];
    println!("原背包: {:?}", backpack3);
    println!("排序后: {:?}", sort_items(&backpack3));
}
```

## 🎨 进阶挑战

完成了基础任务？很好！现在试试这些进阶挑战，获得更多经验值：

### 挑战一：按物品类型分组 🪙（中等）
背包里的物品有不同类型（武器、消耗品、材料）。写一个函数，先按类型分组，再按名称排序。

```javascript
// 进阶挑战1的测试数据
const itemsWithType = [
    { name: "生锈的剑", type: "武器" },
    { name: "治疗药水", type: "消耗品" },
    { name: "魔法卷轴", type: "消耗品" },
    { name: "符文布", type: "材料" },
    { name: "铜币", type: "材料" },
    { name: "精铁长剑", type: "武器" }
];

function groupAndSort(items) {
    // 你的代码：
    // 1. 按 type 分组
    // 2. 每组内按 name 排序
    // 3. 返回分组后的对象
}

console.log(groupAndSort(itemsWithType));
// 预期输出：
// {
//   武器: ["生锈的剑", "精铁长剑"],
//   消耗品: ["治疗药水", "魔法卷轴"],
//   材料: ["铜币", "符文布"]
// }
```

### 挑战二：按自定义规则排序 💎（困难）
有些冒险者喜欢按物品价值排序，有些喜欢按重量。写一个函数，支持传入自定义排序规则。

```javascript
function sortItemsWithRule(items, compareRule) {
    // items: 物品数组
    // compareRule: 比较函数 (a, b) => 负数/0/正数
    // 你的代码
}

// 测试：按名称长度排序
const items = ["长剑", "治疗药水", "魔法卷轴", "符文布"];
console.log(sortItemsWithRule(items, (a, b) => a.length - b.length));
// 应该输出: ["长剑", "符文布", "治疗药水", "魔法卷轴"]（按长度升序）

// 测试：按字母逆序
console.log(sortItemsWithRule(items, (a, b) => b.localeCompare(a)));
```

### 挑战三：背包容量限制 💎（困难）
你的背包只有10个格子，但你有15件物品。写一个函数，选择最有价值的物品放入背包（按价值排序），同时保持名称排序。

```javascript
const valuableItems = [
    { name: "金块", value: 100, weight: 5 },
    { name: "魔法卷轴", value: 80, weight: 1 },
    { name: "治疗药水", value: 50, weight: 1 },
    { name: "铜币", value: 1, weight: 0.1 },
    { name: "银币", value: 10, weight: 0.2 },
    { name: "精铁长剑", value: 200, weight: 8 },
    { name: "魔法宝石", value: 500, weight: 2 }
];

function packBackpack(items, maxSlots) {
    // 你的代码：
    // 1. 按价值排序（高价值优先）
    // 2. 选择前 maxSlots 个物品
    // 3. 再按名称排序
    // 4. 返回最终背包
}

console.log(packBackpack(valuableItems, 5));
// 应该输出价值最高的5件物品，按名称排序
```

## 📝 提交格式

完成委托后，请按以下格式提交：

```markdown
## 基础委托
### 代码
```javascript
function sortItems(items) {
    // 创建副本，避免修改原数组
    const sorted = [...items];
    // 使用默认排序（按Unicode编码）
    sorted.sort();
    return sorted;
}
```

### 运行结果
```
====== 测试用例 1 ======
原背包: ['生锈的剑', '魔法卷轴', '治疗药水', '符文布', '铜币']
排序后: ['铜币', '生锈的剑', '符文布', '魔法卷轴', '治疗药水']
原背包是否改变: ['生锈的剑', '魔法卷轴', '治疗药水', '符文布', '铜币']

====== 测试用例 2 ======
原背包: ['苹果', '香蕉', '橘子', '葡萄']
排序后: ['苹果', '橘子', '葡萄', '香蕉']

====== 测试用例 3 ======
原背包: ['匕首', '盾牌', '长剑', '法杖', '弓箭']
排序后: ['匕首', '弓箭', '长剑', '盾牌', '法杖']
```

## 遇到的困难
中文排序不是按拼音顺序，而是按Unicode编码。解决方法是用 `localeCompare()`：
```javascript
sorted.sort((a, b) => a.localeCompare(b, 'zh-CN'));
```

## 今日感悟
原来排序还有这么多学问！`sort()` 默认是按字符串Unicode编码排序，对于中文需要特殊处理。还学到了 `localeCompare` 的用法。

## 📚 扩展阅读
如果你对数组去重感兴趣，可以看看：[JavaScript 数组去重](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Set)


## 💡 知识点解析

### 本次委托涉及的核心概念

| 概念 | 说明 | 示例 |
|------|------|------|
| **数组复制** | 创建数组副本避免修改原数组 | `const copy = [...arr]` 或 `arr.slice()` |
| **sort() 方法** | 原地排序数组元素 | `arr.sort()` |
| **比较函数** | 自定义排序规则 | `(a, b) => a - b`（数字升序） |
| **localeCompare** | 处理中文排序 | `a.localeCompare(b, 'zh-CN')` |
| **纯函数** | 不修改输入，返回新值 | `sortItems` 不应修改原数组 |

### 常见错误及解决

```javascript
// ❌ 错误1：直接修改原数组
function sortItems(items) {
    return items.sort(); // 直接修改了原数组！
}

// ✅ 正确写法
function sortItems(items) {
    return [...items].sort(); // 先复制再排序
}

// ❌ 错误2：中文排序不正确
['苹果', '香蕉', '橘子'].sort(); 
// 输出: ['苹果', '橘子', '香蕉']（按Unicode，不是按拼音）

// ✅ 正确写法：使用 localeCompare
['苹果', '香蕉', '橘子'].sort((a, b) => a.localeCompare(b, 'zh-CN'));
// 输出: ['橘子', '苹果', '香蕉']（按拼音：jú, píng, xiāng）

// ❌ 错误3：数字排序错误
[1, 2, 10, 20].sort(); 
// 输出: [1, 10, 2, 20]（按字符串排序！）

// ✅ 正确写法：提供比较函数
[1, 2, 10, 20].sort((a, b) => a - b); // 升序
[1, 2, 10, 20].sort((a, b) => b - a); // 降序
```

## 🔥 彩蛋：真正的冒险者背包

如果你想让背包整理更有趣，试试这个真正的冒险者背包类：

```javascript
class AdventurerBackpack {
    constructor(capacity = 20) {
        this.items = [];
        this.capacity = capacity;
    }
    
    addItem(item) {
        if (this.items.length < this.capacity) {
            this.items.push(item);
            this.items.sort((a, b) => a.name.localeCompare(b.name, 'zh-CN'));
            return true;
        }
        return false;
    }
    
    removeItem(itemName) {
        const index = this.items.findIndex(i => i.name === itemName);
        if (index !== -1) {
            return this.items.splice(index, 1)[0];
        }
        return null;
    }
    
    findByType(type) {
        return this.items.filter(i => i.type === type)
            .sort((a, b) => a.name.localeCompare(b.name, 'zh-CN'));
    }
    
    getTotalValue() {
        return this.items.reduce((sum, item) => sum + (item.value || 0), 0);
    }
    
    toString() {
        return this.items.map(i => i.name).join(' · ');
    }
}

// 使用示例
const myBackpack = new AdventurerBackpack(5);
myBackpack.addItem({ name: "生锈的剑", type: "武器", value: 10 });
myBackpack.addItem({ name: "治疗药水", type: "消耗品", value: 50 });
myBackpack.addItem({ name: "魔法卷轴", type: "消耗品", value: 80 });
console.log(myBackpack.toString()); // 自动排序
console.log("消耗品:", myBackpack.findByType("消耗品"));
```

## 🤔 思考题

1. 如果背包里有重复的物品（比如5个铜币），排序时应该怎么处理？
2. 如何实现一个“按最近使用”排序？（像真正的冒险者会把常用物品放上面）
3. 如果物品名称有英文、中文、数字混合，怎么排序才合理？

---

**记住：一个整洁的背包，是专业冒险者的标志！**

*愿你的背包永远井井有条！* 🎒
