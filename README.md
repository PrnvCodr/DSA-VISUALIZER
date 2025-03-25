# **Data Structure Visualizer**  

An interactive platform designed to help learners understand data structures through animated visualizations and step-by-step interactions. Developed using **Next.js 15**, **TypeScript**, **React Flow**, **Framer Motion**, and **Shadcn/ui** for an intuitive and engaging user experience.  

## **Preview**  

![Landing Page](./public/landing-light.png)  
![Stacks](./public/ds-st.png)  
![Queue](./public/ds-q.png)  
![Linked List](./public/ds-ll.png)  
![Polynomial Multiplication](./public/ds-polynomial-multiplication.png)  
![Heap](./public/ds-heap.png)  
![Binary Tree](./public/ds-bst.png)  
![AVL Tree](./public/ds-avl.png)  
![Huffman Encoding](./public/ds-huffman.png)  
![Dijkstra's Algorithm](./public/ds-dijkstra.png)  

---

## **Core Features**  

### **Data Structure Visualizations**  
- **Linked Lists**: Explore **singly**, **doubly**, and **circular** linked lists with dynamic node operations.  
- **Stacks & Queues**: Perform **push/pop** and **enqueue/dequeue** operations with animated feedback.  
- **Trees**: Visualize **Binary Search Trees (BSTs)** and **AVL trees** with self-balancing mechanics.  
- **Heaps**: Watch **min/max heap** insertions and deletions with heapify animations.  

### **Algorithm Applications**  
- **Infix to Postfix Converter**: Demonstrates stack-based expression conversion.  
- **Message Queue Simulation**: Implements a **producer-consumer** queue model.  
- **Polynomial Multiplication**: Uses linked lists to simulate polynomial arithmetic.  
- **Huffman Encoding**: Encodes and decodes text using Huffman trees.  
- **Dijkstra’s Shortest Path**: Finds the optimal path in a weighted graph.  

---

## **Technology Stack**  

- **Framework**: Next.js 15  
- **Language**: TypeScript  
- **Styling**: TailwindCSS  
- **Animations**: Framer Motion  
- **Graph Visualization**: React Flow  
- **UI Components**: Shadcn/ui  

---

## **Getting Started**  

1. Clone the repository:  
   ```bash
   git clone https://github.com/CubeStar1/ds-visualizer.git
   cd ds-visualizer
   ```

2. Install dependencies:  
   ```bash
   npm install
   ```

3. Run the development server:  
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.  

---

## **Project Structure**  

```
ds-visualizer/
├── app/                    # Next.js app router pages
├── components/            
│   ├── ui/                # shadcn/ui components
│   ├── visualizer/        # Data structure visualizations
│   ├── landing/           # Landing page components
│   └── global/            # Global components
├── hooks/                 # Custom React hooks
├── lib/                  
└── content/              # Markdown content for explanations
