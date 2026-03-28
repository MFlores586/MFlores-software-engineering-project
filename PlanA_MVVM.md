#Plan A  - MVVM

### **Overview**

This plan follows a MVVM acrhitecture for implementing the registration page.

### **Components**

#### View (Handles UI and User Input)

-activity_register.xml

-RegisterActivity.ky

#### ViewModel (Validates information and communicates with repository)

-RegisterViewModel.kt

#### Model/Repository (Handles stored user data and registration logic)

-UserRepository.kt

### **Data Flow**
User Inputs Registration Info -> View -> ViewModel -> Repository -> ViewModel -> View
