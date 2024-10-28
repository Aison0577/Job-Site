# Job Portal Website

## Project Overview

This Job Portal website aims to connect job seekers with potential employers. The platform provides a space for job seekers to explore job opportunities, create profiles, and submit applications while enabling employers to post job listings, manage applications, and search for candidates.

## Features

- **Job Seeker Features**:
  - User registration and login
  - Profile creation and editing
  - Job search by keyword, location, and industry
  - Job application submission
  - Dashboard to view applied jobs and application status

- **Employer Features**:
  - Company registration and login
  - Job posting creation and management
  - Dashboard to view and manage applicants
  - Search feature to find potential candidates

- **Admin Features**:
  - User and employer management
  - Job posting approval and moderation
  - Site analytics and insights
  
## Tech Stack

- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token) for secure login
- **File Storage**: Cloud storage for storing resumes and company logos

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory and install dependencies:
   ```bash
   cd job-portal
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```

## User Flow

### 1. Job Seeker Journey

- **Registration/Login**: Users register with basic information, including name, email, and password. After registration, they receive a confirmation email (if email verification is set up).
- **Profile Creation**: Users can create or edit their profile, uploading resumes and adding details like skills, experience, and education.
- **Job Search**: Users can browse or search for jobs based on criteria like job title, location, or company.
- **Application**: Users can view job details and apply, attaching resumes or cover letters if needed.
- **Application Status**: Users have a dashboard to view submitted applications, track the status, and receive feedback.

### 2. Employer Journey

- **Registration/Login**: Employers register with company details, including name, industry, and contact information.
- **Job Posting**: Employers create and post jobs, providing a description, required skills, salary range, and location.
- **Application Management**: Employers can review applicants for each job, filter candidates, and update application statuses.
- **Candidate Search**: Employers can search for potential candidates based on skills, location, or experience to reach out directly if the user has enabled this option.

### 3. Admin Journey

- **User and Job Management**: The admin can monitor and manage users, job listings, and employer accounts, with the authority to approve or suspend any account or job posting.
- **Site Insights**: Admins can access analytics for site traffic, job posting trends, and user engagement statistics.

