# LEETCODE-Arrays-3190
---

## **Initial Setup**

```
nums = [1, 2, 3, 4]
n = 4
result = 0
```

---

## **Loop Iteration**

### **i = 0 → nums[0] = 1**

* 1 % 3 = 1 → NOT 0
* Condition: `else`
  → result = result + 1 = **1**

---

### **i = 1 → nums[1] = 2**

* 2 % 3 = 2 → NOT 0
  → result = result + 1 = **2**

---

### **i = 2 → nums[2] = 3**

* 3 % 3 = 0
  → `continue`
  → result stays **2**

---

### **i = 3 → nums[3] = 4**

* 4 % 3 = 1 → NOT 0
  → result = result + 1 = **3**

---

## **Final Output**

```
return result → 3
```

---

### ✅ **Answer: 3**
