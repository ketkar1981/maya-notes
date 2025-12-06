# 💰 Profit and Loss Cheatsheet

---

## 🔑 Core Concepts & Definitions

| Term | Abbreviation | Definition |
| :--- | :---: | :--- |
| **Cost Price** | **CP** | The price at which an article is purchased. |
| **Selling Price** | **SP** | The price at which an article is sold. |
| **Profit (Gain)** | **P** or **G** | $\text{SP} > \text{CP}$. The extra amount gained after selling. |
| **Loss** | **L** | $\text{CP} > \text{SP}$. The amount lost after selling. |
| **Profit/Loss %** | **P%** or **L%** | The percentage of profit or loss calculated on the **CP**. |
| **Marked Price** | **MP** | The price listed on the article (usually higher than CP). |
| **Discount** | **D** | The reduction offered on the **MP**. Calculated on **MP**. |

---

## 📈 Profit and Loss Formulas

### 1. Basic Calculations

| Situation | Formula | $\LaTeX$ Representation |
| :--- | :--- | :--- |
| **Profit (Gain)** | $\text{Profit} = \text{SP} - \text{CP}$ | $$P = \text{SP} - \text{CP}$$ |
| **Loss** | $\text{Loss} = \text{CP} - \text{SP}$ | $$L = \text{CP} - \text{SP}$$ |
| **No Profit, No Loss** | $\text{SP} = \text{CP}$ | $$\text{SP} = \text{CP}$$ |

### 2. Percentage Calculations (Based on CP)

| Calculation | Formula | $\LaTeX$ Representation |
| :--- | :--- | :--- |
| **Profit %** | $\text{Profit} \% = \frac{\text{Profit}}{\text{CP}} \times 100$ | $$\text{P}\% = \frac{\text{SP} - \text{CP}}{\text{CP}} \times 100$$ |
| **Loss %** | $\text{Loss} \% = \frac{\text{Loss}}{\text{CP}} \times 100$ | $$\text{L}\% = \frac{\text{CP} - \text{SP}}{\text{CP}} \times 100$$ |

### 3. Finding SP/CP with Profit/Loss %

| Target | Formula | $\LaTeX$ Representation |
| :--- | :--- | :--- |
| **Find SP (with Profit %)** | $\text{SP} = \text{CP} \times \left(\frac{100 + \text{P}\%}{100}\right)$ | $$\text{SP} = \text{CP} \left(1 + \frac{\text{P}\%}{100}\right)$$ |
| **Find SP (with Loss %)** | $\text{SP} = \text{CP} \times \left(\frac{100 - \text{L}\%}{100}\right)$ | $$\text{SP} = \text{CP} \left(1 - \frac{\text{L}\%}{100}\right)$$ |
| **Find CP (with Profit %)** | $\text{CP} = \text{SP} \times \left(\frac{100}{100 + \text{P}\%}\right)$ | $$\text{CP} = \frac{100 \times \text{SP}}{100 + \text{P}\%}$$ |
| **Find CP (with Loss %)** | $\text{CP} = \text{SP} \times \left(\frac{100}{100 - \text{L}\%}\right)$ | $$\text{CP} = \frac{100 \times \text{SP}}{100 - \text{L}\%}$$ |

---

## 🏷️ Discount Formulas (Based on MP)

| Calculation | Formula | $\LaTeX$ Representation |
| :--- | :--- | :--- |
| **Discount Amount** | $\text{Discount} = \text{MP} - \text{SP}$ | $$D = \text{MP} - \text{SP}$$ |
| **Discount %** | $\text{Discount} \% = \frac{\text{Discount}}{\text{MP}} \times 100$ | $$\text{D}\% = \frac{\text{MP} - \text{SP}}{\text{MP}} \times 100$$ |
| **Find SP (with Discount %)** | $\text{SP} = \text{MP} \times \left(\frac{100 - \text{D}\%}{100}\right)$ | $$\text{SP} = \text{MP} \left(1 - \frac{\text{D}\%}{100}\right)$$ |
| **Relation between CP, MP, P%** | $\text{CP} \times \left(100 + \text{P}\%\right) = \text{MP} \times \left(100 - \text{D}\%\right)$ | $$\frac{\text{MP}}{\text{CP}} = \frac{100 + \text{P}\%}{100 - \text{D}\%}$$ |

---

## 🔄 Special Cases

### 1. Successive Discounts
If two successive discounts of $D_1\%$ and $D_2\%$ are given, the **Effective Discount %** ($D_{eff}\%$) is:
$$\text{D}_{eff}\% = D_1 + D_2 - \frac{D_1 D_2}{100}$$

### 2. Equal SP, Different P/L %
If two items are sold at the **same SP**, one at a **Profit of $x\%$** and the other at a **Loss of $x\%$**, there is always a **net loss**.
$$\text{Net Loss} \% = \left(\frac{x}{10}\right)^2$$
*(Calculated on the total CP of both items.)*

### 3. Dishonest Dealer (Faulty Weight)
If a dealer pretends to sell at **CP** but uses a weight of $W_{actual}$ instead of the standard weight $W_{true}$:
$$\text{Gain} \% = \left(\frac{W_{true} - W_{actual}}{W_{actual}}\right) \times 100$$
