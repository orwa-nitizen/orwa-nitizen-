



I am a **JacLang Developer & Python Programmer** passionate about building **dynamic scripts, AI-driven projects, and interactive graph systems**.  

---

## 🚀 Tech Stack

![JacLang](https://img.shields.io/badge/JacLang-FF6F61?style=for-the-badge&logo=JacLang&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![NetworkX](https://img.shields.io/badge/NetworkX-000000?style=for-the-badge&logo=networkx&logoColor=white)

---

## 🌟 Featured Projects

### 1️⃣ Family Graph Tree Generator
**Technologies:** JacLang + Python  

A dynamic **family tree generator** that supports **interactive input** and produces **graphical outputs**.  

- JacLang handles **graph creation and relationships**  
- Python powers **visualization and AI-based analysis**  
- Add, remove, and query family members dynamically  

```jac
# JacLang snippet: Create family relationships
with entry {
    graph family;
    family.add_node("Alice");
    family.add_node("Bob");
    family.add_edge("Alice", "Bob");
    print(family);
}


# Python snippet: Visualize family graph
import networkx as nx
import matplotlib.pyplot as plt

G = nx.DiGraph()
G.add_edge("Alice", "Bob")

plt.figure(figsize=(6,6))
nx.draw(G, with_labels=True, node_color='skyblue', node_size=2000, arrowsize=20)
plt.show()
