# Remote Procedure Calls (RPC) 🖥️

> **ℹ️ Info**  
> In **distributed computing**, a **Remote Procedure Call (RPC)** allows a computer program to execute a procedure (subroutine) in a **different address space** (often on another computer in a shared network).  

---

## 🔑 Key Idea

- Written **as if it were a normal local function call**  
- The programmer does **not** need to write networking details  
- Code looks the same whether the subroutine is local or remote  

---

## ⚙️ Client–Server Model

- **Caller** → the client (requests the procedure)  
- **Executor** → the server (runs the procedure)  
- Communication is handled via a **request–response message-passing system**  

---

## 📌 Why It Matters

RPC abstracts away low-level networking details.  
Developers can focus on **functionality**, while RPC handles:  
- Packaging the request  
- Sending it to the server  
- Executing the procedure remotely  
- Returning the response back to the client  

