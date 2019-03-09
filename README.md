# School-Machine Design

School machine has a number of architectural components, each of which are small in enough in complexity to easily understand the domain aspects, and be to be easily implemented in multiple technologies, as new technologies appear.

The goal of this project is not create a fully functional web and mobile enabled application, but to identify the architectural components and patterns necessary to create a minimally viable product.

# SchoolMachine SchoolData Entity Model

![SchoolData-Entity-Model-1](Architecture/SchoolMachineEntityModel_00001.png)

# Application Architectural Components

![school-list-1](Architecture/Application/ApplicationComponents_00001.png)

* School-Machine Client
* Authentication & Authorization Service
* District Service
* DistrictSchool Service
* School Service
* Student Service
* SchoolStudent Service
* Database

# School-Machine Client Anatomy

The School-Machine client application will be implemented in multiple web development technology frameworks.  Currently, there are three technologies under study:

  | Framework  |  Repository | Version  | Status  |   |
|---|---|---|---|---|
|  Angular |  SchoolMachineUIAngular | 7  |  In Development |   |
|  React | schoolmachineuireact  |   | Very Rough Start  |   |
|  MVC/Razor |  na |  .net core 2.2 | Not Started  |   |
  

## App Module

The App module contains the menu component and the router.

## Child Components

### Menu

![menu-1](MockUp/Components/Menu/SchoolMachine_Menu_0001.png)

### Home

![app-1](MockUp/Components/Home/SchoolMachine_Home_0001.png)

### School

* school-list

![school-list-1](MockUp/Components/School/school-list/SchoolMachine_school-list_0001.png)

* school-create

![school-create-1](MockUp/Components/School/school-create/SchoolMachine_school-create_0001.png)

* school-delete

![school-delete-1](MockUp/Components/School/school-delete/SchoolMachine_school-delete_0001.png)

* school-details

![school-details-1](MockUp/Components/School/school-details/SchoolMachine_school-details_0001.png)

* school-update

![school-update-1](MockUp/Components/School/school-update/SchoolMachine_school-update_0001.png)

### Student

* student-list

![student-list-1](MockUp/Components/Student/student-list/SchoolMachine_student-list_0001.png)

* student-create

![student-create-1](MockUp/Components/Student/student-create/SchoolMachine_student-create_0001.png)

* student-delete

![student-delete-1](MockUp/Components/Student/student-delete/SchoolMachine_student-delete_0001.png)

* student-details

![student-details-1](MockUp/Components/Student/student-details/SchoolMachine_student-details_0001.png)

* student-update

![student-update-1](MockUp/Components/Student/student-update/SchoolMachine_student-update_0001.png)

# School-Machine Web Services

* Swagger

![Swagger-1](Architecture/Application/Services/SchoolMachine_SwaggerServices_0001.png)

![Swagger-2](Architecture/Application/Services/SchoolMachine_SwaggerServices_0002.png)