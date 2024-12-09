# StudyNotion Online Education Platform (MERN App)  


## Description  
StudyNotion is an ed-tech platform for creating, consuming, and rating educational content. Built with the MERN stack (ReactJS, NodeJS, MongoDB, ExpressJS), it offers an interactive experience for students and a showcase platform for instructors.  

## System Architecture  
### Front End  
- Built with ReactJS for dynamic UI, styled using Tailwind CSS.  
- State management handled by Redux.  
- Communicates with the backend via RESTful APIs.  

### Back End  
- Built with Node.js and Express.js.  
- Features include user authentication, course management, Razorpay payment integration, and Cloudinary for media management.  

### Database  
- MongoDB is used for flexible and scalable data storage.  

## Key Features  
### Students  
- Access courses, wishlist, cart, and course content.  

### Instructors  
- Dashboard, insights, and course management.  

### Admin (Future Scope)  
- Platform management, user management, and advanced analytics.  

## API Endpoints  
### User  
- `/api/auth/signup` - Create a user account.  
- `/api/auth/login` - Log in and generate a JWT token.  
- `/api/auth/verify-otp` - Verify OTP for account security.  
- `/api/auth/forgot-password` - Request a password reset.  

### Courses  
- `/api/courses` - Get or create courses.  
- `/api/courses/:id` - Retrieve, update, or delete a course.  
- `/api/courses/:id/rate` - Add a rating to a course.  

## Tools and Frameworks  
- **Frontend:** ReactJS, Redux, Tailwind CSS.  
- **Backend:** Node.js, Express.js, MongoDB, JWT, Bcrypt, Cloudinary, Razorpay.  

## Future Enhancements  
- Admin dashboard, advanced analytics, and expanded platform functionalities.  
