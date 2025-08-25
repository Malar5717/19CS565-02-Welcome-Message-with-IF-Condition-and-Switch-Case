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
