# Web Project

A professional website showcasing services and company presence in Malaysia and Singapore.

![Malaysia Office](images/malaysia.png) ![Singapore Office](images/singapore.png)

## Project Structure
Trae

Great! The README.md file has been created successfully. You can now:

1. Add it to your Git repository:
```
git add README.md
git commit -m "Add README.md"
```
2. Push it to GitHub:
```
git push origin main
```
Remember to update the License and Contact sections with your specific information before pushing to GitHub. Is there anything else you'd like me to help you with?

haneul sky

Copy

Delete

but why the picture iin github is not appear?

Trae

To make images appear in GitHub README, you need to use the correct markdown syntax and ensure the image paths are relative to your repository. Here's how to fix it:

1. For images in your repository, use this format:
```
![image description](images/malaysia.png)
![image description](images/singapore.png)
```
2. Make sure your image paths are correct and use forward slashes (/) even on Windows
3. If you want to add other images from your project, you can reference them similarly:
```
![CAD/CAM](images/cad.jpg)
![CNC Operations](images/cnc.jpg)
![PCB Assembly](images/pcb.jpg)
![SMT Services](images/smt.jpg)
```
Would you like me to update the README with these image references?

haneul sky

Copy

Delete

yes

Trae

Let me check the current README content before updating it with image references.

README.md :( 1 - 100 )

I'll update the README.md with proper image references and enhanced content. Here's the improved version:

```
# Web Project

A professional website showcasing services 
and company presence in Malaysia and 
Singapore.

![Malaysia Office](images/malaysia.png) !
[Singapore Office](images/singapore.png)

## Project Structure

```
├── about.html
├── contact.html
├── services.html
├── index.html
├── footer.html
├── styles.css
├── config.php
├── send-mail.php
└── images/


## Features

- Responsive web design
- Contact form with PHP mailer integration
- Service showcase pages
- Company information and locations
- Image gallery showcasing various services including:

### Our Services
![CAD/CAM](images/cad.jpg) ![CNC Operations](images/cnc.jpg)
![PCB Assembly](images/pcb.jpg) ![SMT Services](images/smt.jpg)
![Precision Engineering](images/precision.jpg) ![Quality Inspection](images/inspection.jpg)

## Technologies Used

- HTML5
- CSS3
- PHP
- PHPMailer
- Composer (PHP package manager)

## Setup

1. Clone the repository
2. Install dependencies:
```bash
composer install
