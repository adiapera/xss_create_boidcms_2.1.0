# XSS in BoidCMS 2.1.0 (/admin -> Create)
**Software link:** BoidCMS 2.1.0 [https://boidcms.github.io/#/] -> Download

**@author:** Antonio Díaz.

**Description:** Cross-site scripting (XSS) vulnerability in the Create section of the Admin Page of BoidCMS 2.1.0 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into 'Permalink' parameter.

**CVE:** CVE-2024-32342.

## PoC
### Admin Page -> Create (CVE-2024-32342)
1. Enter to Create section of Admin Page, set the payload in 'Permalink' parameter and click on the Create button:

![image](https://github.com/adiapera/xss_create_boidcms_2.1.0/assets/165512291/2a2a96b9-c0e8-4701-a0f0-0e5cbb8a38cc)
![image](https://github.com/adiapera/xss_create_boidcms_2.1.0/assets/165512291/c533caf2-01af-4c75-a177-db6c8f39fc8b)
![image](https://github.com/adiapera/xss_create_boidcms_2.1.0/assets/165512291/e1c9dced-050b-4390-93dd-1d43675f6633)

2. Show Dashboard page and click on the Update or Delete menu:
![image](https://github.com/adiapera/xss_create_boidcms_2.1.0/assets/165512291/dfda935d-d25a-44fc-969a-1479de257825)
![image](https://github.com/adiapera/xss_create_boidcms_2.1.0/assets/165512291/1bcd24ff-b955-4209-97d2-5d1a5db4a47b)


