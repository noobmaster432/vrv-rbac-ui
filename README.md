# Role-Based Access Control (RBAC) UI  

## **Overview**  

This project is a **Role-Based Access Control (RBAC)** User Interface implemented using **React.js (Vite)**, **TypeScript**, **Tailwind CSS**, and **Zustand** for state management. It provides an intuitive admin dashboard for managing users, roles, and permissions efficiently and securely.  

---

## **Features**  

### **1. User Management**  
- View, add, edit, and delete users.  
- Assign roles to users and manage their statuses (Active/Inactive).  
- Intuitive UI for seamless user management.  

### **2. Role Management**  
- Create, update, and delete roles.  
- Define roles with custom attributes and associated permissions.  
- Clearly display the relationship between roles and permissions.  

### **3. Dynamic Permissions**  
- Assign, modify, or revoke permissions for roles dynamically.  
- Permissions are presented in an easy-to-navigate and user-friendly interface.  
- Real-time updates for changes in roles and permissions.  

### **4. Mock API Integration**  
- Simulates CRUD operations for users, roles, and permissions.  
- Mimics server responses to validate the functionality of the UI.  

---

## **Technology Stack**  

### **Frontend**  
- **Framework**: React.js (Vite)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand

### **API Simulation**  
- Mock API for handling CRUD operations.  

---

## **Setup Instructions**  

### **1. Prerequisites**  
- Node.js and npm installed.  
- A code editor like Visual Studio Code.  

### **2. Installation**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/noobmaster432/vrv-rbac-ui.git
   cd vrv-rbac-ui
   ```  
2. Install dependencies:  
   ```bash  
   npm install
   ```  

### **3. Running the Project**  
- Start the development server:  
  ```bash  
  npm run dev 
  ```  

---

## **Demo Workflow**  

### **User Management**  
- Access the **Users** section to manage users.  
- Add a new user by filling in required details and assigning roles.  
- Edit user information, toggle their status (Active/Inactive), or delete users.  

### **Role Management**  
- Navigate to the **Roles** section.  
- Create new roles with customizable permissions and attributes.  
- Edit or delete existing roles.  

### **Permissions Management**  
- View and modify permissions associated with roles in the **Permissions** section.  
- Add or remove permissions dynamically to maintain proper access control.  

---

## **Enhancements**  

- **Responsive Design**: Optimized for both desktop and mobile views.  
- **State Management**: Zustand ensures efficient and scalable state handling.  
- **Search and Filter**: Quickly find users or roles with search and filter options.  
- **Error Handling**: Graceful handling of edge cases with user-friendly error messages.  

---

## **Folder Structure**  
```plaintext  
rbac-ui/  
├── src/  
│   ├── components/        # Reusable UI components  
│   ├── pages/             # Page-level components (Users, Roles, Permissions)  
│   ├── stores/            # Zustand state management files  
│   ├── types/             # TypeScript types and interfaces  
│   ├── utils/             # Utility functions  
│   ├── App.tsx            # Root component  
│   └── main.tsx           # Entry point  
├── public/                # Static assets  
├── tailwind.config.js     # Tailwind CSS configuration  
├── tsconfig.json          # TypeScript configuration  
└── vite.config.ts         # Vite configuration  
```  

---

## **Live Demo**  
Check out the live demo here: [Live Demo](https://vrv-rbac-ui.vercel.app/)  

---

## **License**  
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.  

------------
