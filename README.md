# We will explore tenant-level logging and KQL in Azure.

## Go to portal.azure.com and sign in > search "Entra" > "diagnostic settings" > "add diagnostic settings" 

<img src="https://github.com/VanessaMancia/Intra-AD-KQL/assets/112146207/9a39cf56-28c2-4f1c-ac92-58fe09d641c4.png">
---

## Create a dummy user, username “dummy_user” 

<img src="https://github.com/VanessaMancia/Intra-AD-KQL/assets/112146207/98722675-7039-4444-a699-c0ad0c4ec6d5.png">
---

## Log in with it once (incognito window) (Make sure to get the user principal name and password so you can log in) 

<img src="https://github.com/VanessaMancia/Intra-AD-KQL/assets/112146207/a7cb9410-30ca-4597-b502-278dd8b5571c.png">

---

## Assign dummy_user the Role of Global Administrator and then delete dummy_user
### Click "Azure role assignments" > "Add Assignments" > search "Global administrator" 

<img src="https://github.com/VanessaMancia/Intra-AD-KQL/assets/112146207/b1923c9e-df50-4637-94dc-fe0ac56f2ee2.png">

---

## Now let's go Work Analytics workspace and use KQL to query our audit logs 

<img src="https://github.com/VanessaMancia/Intra-AD-KQL/assets/112146207/a4dda522-81c3-4951-95ff-3db723123f11.png">

---

