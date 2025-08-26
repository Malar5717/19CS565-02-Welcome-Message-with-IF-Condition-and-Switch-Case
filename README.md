# Exercise 2: Welcome Message with IF Condition and Switch Case

## Part A

### Aim
To display a custom welcome message using **IF condition** in UiPath, based on user input.

### Procedure  
1. Create a new UiPath project → **WelcomeMessageIf**.  
2. Open **Main.xaml**.  
3. Add an **Input Dialog** activity:  
   - Title: "Enter Name"  
   - Label: "What is your name?"  
   - Store result in variable → `userName`.  
4. Insert an **If activity**:  
   - Condition: `userName.ToUpper = "RAM"`  
   - Then → Message Box: `"Welcome Mr. Ramachandran"`  
   - Else → Message Box: `"Welcome " + userName`  
5. Save and run the workflow.  
6. Test with different names.

### Output
<img width="1594" height="840" alt="image" src="https://github.com/user-attachments/assets/d2cf912a-abcb-40ce-b64f-8592e45c357d" />
<img width="1596" height="839" alt="image" src="https://github.com/user-attachments/assets/8a317546-1a64-481f-9feb-408e353eb902" />
<img width="1596" height="842" alt="image" src="https://github.com/user-attachments/assets/f4068a45-5bde-41a6-88c9-4137dec98fd0" />
<img width="1593" height="843" alt="image" src="https://github.com/user-attachments/assets/3ca1c25f-1602-4c4f-bf7a-2879cd569734" />
<img width="1600" height="844" alt="image" src="https://github.com/user-attachments/assets/566a89e0-38ff-43aa-ae4a-1d3b7a14af0c" />


## Part B

### Aim  
To display a custom welcome message using **Switch Case** in UiPath, based on user input.

### Procedure  
1. Create a new workflow `SwitchCase.xaml` in the same project.  
2. Add an **Input Dialog** activity:  
   - Title: "Enter Name"  
   - Label: "What is your name?"  
   - Store result in variable → `userName`.  
3. Insert a **Switch activity**:  
   - Expression: `userName.ToUpper`  
   - TypeArgument: `String`.  
4. Define cases:  
   - Case `"ALICE"` → Message Box: `"Welcome Alice! Have a great day."`  
   - Case `"BOB"` → Message Box: `"Hi Bob! Welcome back."`  
   - Case `"CHARLIE"` → Message Box: `"Hello Charlie, glad to see you!"`  
   - Default → Message Box: `"Hello " + userName + ", Welcome!"`  
5. Save and run the workflow.  
6. Test with different names.

   ### Output

   <img width="1519" height="839" alt="image" src="https://github.com/user-attachments/assets/86337171-a80e-45c6-9339-274b576ec1e0" />
   <img width="1521" height="846" alt="image" src="https://github.com/user-attachments/assets/edc4a77b-2f43-428b-a5d9-b7ad160aa11e" />
<img width="1512" height="843" alt="image" src="https://github.com/user-attachments/assets/79955666-f053-473d-b086-4a3215f6c1c7" />
<img width="1518" height="851" alt="image" src="https://github.com/user-attachments/assets/1b22c7ba-1586-42ec-bb29-495ec22c519f" />
<img width="1510" height="829" alt="image" src="https://github.com/user-attachments/assets/1543002b-b657-4f9c-bae0-2c04c4926d0c" />
<img width="1520" height="845" alt="image" src="https://github.com/user-attachments/assets/a3287957-059c-491a-bb8c-8503949aaef4" />
<img width="1513" height="841" alt="image" src="https://github.com/user-attachments/assets/a10e6427-6fa9-4c62-b8ac-38dfa8b65df7" />


### Result
The execution of displaying Welcome Message using If and SwitchCase is completed successfully.
   
