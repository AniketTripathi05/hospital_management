# hospital_management



![Image](https://github.com/user-attachments/assets/17de4f3f-c2f3-4496-b7ac-d9089968b17f)




![Image](https://github.com/user-attachments/assets/61bddabe-ebdf-4d88-88c5-9ca62d64b749)







![Image](https://github.com/user-attachments/assets/7b67448a-5429-40e0-b170-2d7f51bbc4a6)



![Image](https://github.com/user-attachments/assets/06335bf2-cb03-4c15-85a6-eaee06157df1)




![Image](https://github.com/user-attachments/assets/76cc1fb9-24d9-4d8f-b745-c5f8c321ec87)











# Functions

#Admin
1.Create Admin account using following command
2. py manage.py createsuperuser
After Login, can see Unit of blood of each blood group available, Number Of Donor, Number of blood request, Number of approved request, Total Unit of blood on Dashboard.
Can View, Update, Delete Donor.
Can View, Update, Delete Patient.
Can View Donation Request made by donor and can approve or reject that request based on disease of donor.
If Donation Request approved by admin then that unit of blood added to blood stock of that blood group.
If Donation Request rejected by admin then 0 unit of blood added to stock.
Can View Blood Request made by donor / patient and can approve or reject that request.
If Blood Request approved by admin then that unit of blood reduced from blood stock of that blood group.
If Blood Request rejected by admin then 0 unit of blood reduced from stock.
Can see history of blood request.
Can Update Unit Of Particular Blood Group.


# Donor
Donor can create account by providing basic details.
After Login, Donor can donate blood, After approval from admin only, blood will be added to blood stock.
Donor can see their donation history with status (Pending, Approved, Rejected).
Donor can also request for blood from blood stock.
Donor can see their blood request history with status.
Donor can see number of blood request Made, Approved, Pending, Rejected by Admin on their dashboard.
NOTE: Donor can donate blood and can also request for blood.


# Patient

Create account (No Approval Required By Admin, Can Login After Signup)
After Login, Can see number of blood request Made, Approved, Pending, Rejected by Admin on their dashboard.
Patient can request for blood of specific blood group and unit from blood stock.
Patient can see their blood request history with status (Pending, Approved, Rejected).


# HOW TO RUN THIS PROJECT

Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
Download This Project Zip Folder and Extract it
Move to project folder in Terminal. Then run following Commands :
python -m pip install -r requirements. txt
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
Now enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:8000/


# for any error/ feedback, just ping me up here in github
