project-root/
├── client/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── components/
│   │   │   ├── auth/
│   │   │   │   ├── Login.js
│   │   │   │   └── Register.js
│   │   │   ├── teacher/
│   │   │   │   ├── CreateAssignment.js
│   │   │   │   └── ViewSubmissions.js
│   │   │   ├── student/
│   │   │   │   ├── AssignmentList.js
│   │   │   │   └── SubmitAssignment.js
│   │   │   └── shared/
│   │   │       ├── Layout.js
│   │   │       └── PrivateRoute.js
│   │   ├── context/
│   │   │   └── AuthContext.js
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── TeacherDashboard.js
│   │   │   └── StudentDashboard.js
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   ├── authService.js
│   │   │   └── assignmentService.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── index.css
│   └── package.json
├── server/
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── assignmentController.js
│   │   └── submissionController.js
│   ├── middleware/
│   │   ├── auth.js
│   │   └── cache.js
│   ├── models/
│   │   ├── User.js
│   │   ├── Assignment.js
│   │   └── Submission.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── assignmentRoutes.js
│   │   └── submissionRoutes.js
│   ├── config/
│   │   └── db.js
│   ├── server.js
│   └── package.json
├── docker-compose.yml
└── README.md
