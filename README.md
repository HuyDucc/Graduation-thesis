                                                ===== TÀI LIỆU KHÓA LUẬN TỐT NGHIỆP =====
                                                
Tài liệu chia sẻ cho tất cả mọi người nên vui lòng không share link
Em thìn đã tổng hợp file vào 1 folder ở trên nên mọi người vào file ở trên để làm việc và chỉnh sửa. vui lòng không sử dụng những file ở dưới nữa.
    
1. Folder Khóa luận tốt nghiệp: https://drive.google.com/drive/folders/1M67A1Z6urx3KlgnAwv4SyENAtGPW9zca?usp=sharing
2. Design: https://www.figma.com/file/p97J0mutkQUwwZhzG96obC/KLTN?node-id=0%3A1




////////////// không sử dụng tài liệu ở dưới này nữa nhé.


    1.Proposal: https://docs.google.com/document/d/1gYEidWT7AJmx9d56mM6gq1vlRJIvhOm6ECZ1KecNR9Q/edit?fbclid=IwAR1n3epPYvfHOhiU_Y7wyUxf-DpM0qh8bqW9APE3hul2K9tEad12wo-61TE

    2.User Story_KL :https://docs.google.com/document/d/1NejBJFZhEcatmj_G3C51KpoUvhK6SixhuxHCaxVnkIA/edit#

    3.ProductBacklog_KL : https://docs.google.com/document/d/1daPPWnOR-g_wjuNjyJDk4t33Fo6n8o0dQKyifkAoG_c/edit#

    4.Project Plan_KL : https://docs.google.com/document/d/1zGEfb02bkzrneASI5qHf3eJQ2W_TuW2ekhU7Ic4pJ-A/edit

    5.Sprint_Backlog_KL :https://docs.google.com/spreadsheets/d/1QNZqaqifjX7yvHJ2M7ySx9TCC27AnyCZd49m4Q1tNp4/edit?usp=sharing

    6.User_Interface_Design_Sprint_KL : https://docs.google.com/document/d/1XaNPCgHaJhdVemaYb8GS4DDobRbzrNrWFPqNIvxgg_c/edit?usp=sharing

    7.Database_KL : https://docs.google.com/document/d/1i8_R8-ZPlQPOK0jDpwthJhqZpWJqPtFjTuZVFENiT5M/edit?usp=sharing 

    8.Testcase_Sprint1_KL : https://docs.google.com/spreadsheets/d/1YaHBavustljSUfVtxUb093DK38zE1EOd8FWasWRBVVM/edit?usp=sharing

    8.Testcase-Sprint2_KL : https://docs.google.com/spreadsheets/d/1wp_wTBZ00_7P7TuFKCpa7FKPYTZ0TBJQj4U5PtQ9iWM/edit?usp=sharing

    9.Test-Plan-Sprint1_KL :https://docs.google.com/document/d/1AmcaxcqMsk2duAZkur-Y_IWi8ekfhN2EJWz1lEShvl8/edit?usp=sharing

    9.Test-Plan-Sprint2_KL :https://docs.google.com/document/d/1VZRTRV3JC7DJFec2oGNQ9syZoKYJQcEVOgIQPJbI4Zg/edit

    10.Meeting-Sprint1 :https://docs.google.com/document/d/18UV3E657DZDLnnIAEJ6fup_FeIVf9dLs7Ucliox5gOw/edit?usp=sharing

    10.Meeting-Sprint2 :https://docs.google.com/document/d/1vRa6Y0s0FtSvebZshoE6Q_CVM-RgSUW1zdjKqF_7s3Q/edit?usp=sharing

    10.Meeting-Final:https://docs.google.com/document/d/1sdPJuSGFUqOkm6KyrPinFyNXkKvQkZniI20DL2vgKmk/edit?usp=sharing


// USER
  
  Login 

    POST  http://localhost:8081/user/login
    
    {
        "email": "admin.wer@gmail.com",
        "password": "1q2w3e456789"
    }
  
  Register

    POST  http://localhost:8081/user/register
    
    {
        "firstName": "Benjamin",
        "lastName": "Wan",
        "email": "benjaminffff@gmail.com",
        "username": "benjamin_ertffggg",
        "roles": "ROLE_USER",
        "password": "1q2w3e456789"
    }
    
  Reset password
    
    GET  http://localhost:8081/user/resetPassword/<email>
    
  Add user

    POST http://localhost:8081/user/add
    
    Res
        
  ![image](https://user-images.githubusercontent.com/73837629/167130033-033a5b6e-e7ea-4e4f-b198-b8398c9f0e3e.png)

    Req

    {
        "id": 69,
        "firstName": "James",
        "lastName": "Wan",
        "username": "james1",
        "email": "admin@gmail.com",
        "phoneNumber": null,
        "dateOfBirth": null,
        "profileImageUrl": "http://localhost:8081/user/image/profile/james1",
        "lastLogin": null,
        "lastLoginDateDisplay": null,
        "joinDate": "2022-05-06T12:19:58.416+00:00",
        "roles": "ROLE_TEACHER",
        "authorities": [
            "user:create",
            "user:delete",
            "user:read",
            "user:update"
        ],
        "authType": null,
        "active": true,
        "notLocked": true
    }
    
    Update User

    POST http://localhost:8081/user/update
    
    Req

  ![image](https://user-images.githubusercontent.com/73837629/167130625-894d9286-6b6d-47fa-a1f7-281af93df333.png)

    Res
    
    {
        "id": 48,
        "firstName": "Jamesss",
        "lastName": "Wannn",
        "username": "jamesss22222",
        "email": "james@gmail.com",
        "phoneNumber": null,
        "dateOfBirth": null,
        "profileImageUrl": "http://localhost:8081/user/image/profile/wang_huy",
        "lastLogin": "2022-04-11T15:22:20.039+00:00",
        "lastLoginDateDisplay": "2022-04-11T15:19:45.037+00:00",
        "joinDate": "2022-05-30T16:29:55.332+00:00",
        "roles": "ROLE_USER",
        "authorities": [
            "user:read",
            "user:update"
        ],
        "authType": null,
        "notLocked": true,
        "active": true
    }
    
    Delete User

    DELETE http://localhost:8081/user/delete/50
    
    Res

    {
        "timeStamp": "05-06-2022 07:28:34",
        "httpStatusCode": 200,
        "httpStatus": "OK",
        "type": "SUCCESS",
        "reason": "OK",
        "message": "USER DELETED SUCCESSFULLY"
    }
    
    List User

    GET http://localhost:8081/user/list
    
    [
        {
            "id": 11,
            "firstName": "Ho Quang",
            "lastName": "Huy",
            "username": "quanghuy",
            "email": "admin@gmail.com",
            "phoneNumber": null,
            "dateOfBirth": null,
            "profileImageUrl": "http://localhost:8081/user/image/profile/quanghuy",
            "lastLogin": "2022-05-06T12:21:11.135+00:00",
            "lastLoginDateDisplay": "2022-05-06T08:30:26.513+00:00",
            "joinDate": "2022-03-14T15:44:04.115+00:00",
            "roles": "ROLE_ADMIN",
            "authorities": [
                "user:create",
                "user:delete",
                "user:read",
                "user:update"
            ],
            "authType": null,
            "notLocked": true,
            "active": true
        }
    ]
    
    
    Change password

    POST http://localhost:8081/user/change-password
    
    Res
    
    {
      "email": "james@gmail.com",
      "oldPassword": "RZnsso57",
      "newPassword": "1q2w3e456789"
    }
    
    Req
    
    {
      "timeStamp": "05-06-2022 07:32:24",
      "httpStatusCode": 200,
      "httpStatus": "OK",
      "type": "SUCCESS",
      "reason": "OK",
      "message": "CHANGE PASSWORD SUCCESSFULLY"
    }
    
    
    Lock account 
    
    GET http://localhost:8081/user/44/locked/true
    
    {
      "timeStamp": "05-06-2022 07:33:40",
      "httpStatusCode": 200,
      "httpStatus": "OK",
      "type": "SUCCESS",
      "reason": "OK",
      "message": "ACCOUNT UNLOCK SUCCESSFUL"    like LOCK
    }
    
    
    Export User CSV

    Req
    
    GET http://localhost:8081/user/export/csv

    
    
    Quiz

    Add Quiz 
    
    POST http://localhost:8081/quizz/add

  [image](https://user-images.githubusercontent.com/73837629/167132479-12f5e8c6-f9e0-4ddf-8fe9-b88f97b5be4e.png)
    

    Req
    
    {
      "timeStamp": "05-06-2022 07:36:37",
      "httpStatusCode": 200,
      "httpStatus": "OK",
      "type": "SUCCESS",
      "reason": "OK",
      "message": "ADD QUICK TEST SUCCESS"
    }
    
    List quiz

    GET http://localhost:8081/quizz/list

    Res

    [
        {
            "id": 4,
            "testName": "java",
            "dateCreated": "29-03-2022 09:53:17",
            "examTime": 600,
            "isStart": null,
            "isEnd": null,
            "activationCode": "236759",
            "questions": [
                {
                    "id": 3,
                    "topicQuestion": "How can you achieve runtime polymorphism in Java?",
                    "questionImageUrl": "",
                    "answerA": "method overloading",
                    "answerB": "method overrunning",
                    "answerC": "method overriding",
                    "answerD": "method calling",
                    "correctResult": "C",
                    "mark": 2.5,
                    "milestones": 1,
                    "dateCreated": "11-04-2022 10:11:33"
                },
                {
                    "id": 5,
                    "topicQuestion": "The runtime system starts your program by calling which function first?",
                    "questionImageUrl": null,
                    "answerA": "print",
                    "answerB": "iterative",
                    "answerC": "hello",
                    "answerD": "main",
                    "correctResult": "D",
                    "mark": 2.5,
                    "milestones": 1,
                    "dateCreated": "11-04-2022 10:11:33"
                },
                {
                    "id": 78,
                    "topicQuestion": "The runtime system starts your program by calling which function first?",
                    "questionImageUrl": null,
                    "answerA": null,
                    "answerB": null,
                    "answerC": null,
                    "answerD": null,
                    "correctResult": null,
                    "mark": 2.5,
                    "milestones": 1,
                    "dateCreated": null
                }
            ]
        }
     ]     
    



    
    
    
    


 

