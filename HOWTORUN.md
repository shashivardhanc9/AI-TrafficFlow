### **🚀 How to Run the AI Traffic Management System**  

Since this project involves **AI-based traffic control**, here’s a **step-by-step guide** to running it smoothly.  

---

## **🔹 Step 1: Install Dependencies**  
Before running the simulation, install all required Python libraries. Open a terminal and run:  
```bash
pip install neat-python pygame matplotlib opencv-python numpy
```

---

## **🔹 Step 2: Run the Simulation**  
Navigate to the project folder and execute the simulation script:  
```bash
python simulation.py
```
✅ This will start the **AI-based traffic system visualization**.

---

## **🔹 Step 3: If Using NEAT AI (Optional)**  
If you want to enable **NeuroEvolution of Augmenting Topologies (NEAT)** for AI training, do this:  
1. **Download the NEAT config file** from:  
   🔗 [Download NEAT Config File](https://techwithtim.net/wp-content/uploads/2019/08/config-feedforward.txt)  
2. **Save it as `config.txt` in your project folder.**  
3. **Run the NEAT-powered AI:**  
   ```bash
   python simulation.py --neat
   ```

---

## **🔹 Step 4: Adjusting Simulation Parameters**  
If needed, modify **traffic light timings or AI behavior** by editing:  
- `simulation.py` → **Core AI traffic logic**  
- `config.txt` → **NEAT AI settings**  

---

## **🔹 Step 5: Stopping the Simulation**  
To **exit the simulation**, simply close the window or press:  
```bash
CTRL + C
```

---

