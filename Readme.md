
# Job Portal Website

## Project Overview

This Job Portal website connects job seekers with potential employers. The platform provides a space for job seekers to explore job opportunities, create profiles, and submit applications, while enabling employers to post job listings, manage applications, and search for candidates.

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

- **Backend**: Laravel
- **Database**: MySQL (or compatible)
- **Frontend**: Blade templates, HTML, CSS, JavaScript
- **Authentication**: Laravel Sanctum or Laravel Passport for secure login
- **File Storage**: Laravel File Storage for storing resumes and company logos

## User Flow

### 1. Job Seeker Journey

- **Registration/Login**: Job seekers register with their name, email, and password. After registration, they may receive a confirmation email (if email verification is enabled).
- **Profile Creation**: Users create or edit their profile with details like skills, experience, and education, and upload resumes.
- **Job Search**: Users can browse or search for jobs based on job title, location, or company.
- **Application**: Users view job details and apply, attaching resumes or cover letters as needed.
- **Application Status**: Users have a dashboard to track submitted applications, view status updates, and receive feedback.

### 2. Employer Journey

- **Registration/Login**: Employers register with company details such as name, industry, and contact information.
- **Job Posting**: Employers create job listings with descriptions, required skills, salary range, and location.
- **Application Management**: Employers review applicants, filter candidates, and update application statuses.
- **Candidate Search**: Employers can search for candidates based on skills, location, or experience, reaching out if the candidate has enabled direct contact.

### 3. Admin Journey

- **User and Job Management**: The admin manages users, job listings, and employer accounts with the authority to approve, suspend, or modify accounts and postings.
- **Site Insights**: Admins access analytics for site traffic, job trends, and user engagement metrics.
