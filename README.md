# 🛡 LAB: Active Directory
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active%20Directory-19b5fe?style=for-the-badge&logo=microsoft&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-0A84FF?style=for-the-badge&logo=powershell&logoColor=white)
![Windows 10](https://img.shields.io/badge/Windows%2010-3366CC?style=for-the-badge&logo=windows&logoColor=white)

---

## 🌟 Descripción

Laboratorio práctico orientado a la instalación y configuración básica de **Active Directory Domain Services (AD DS)** en un entorno aislado con **Windows Server**.  
Incluye la creación de un dominio, usuarios, grupos, políticas de contraseñas y permisos sobre recursos compartidos, con el objetivo de reforzar habilidades esenciales para roles de **Blue Team / SOC / Administración de Sistemas**.

---

## 🎯 Objetivos principales

• Implementar un **dominio AD DS** (`lab.local`) en Windows Server.  
• Crear y organizar **Unidades Organizativas (OUs)**.  
• Administrar **usuarios, grupos y roles**.  
• Configurar **políticas de contraseñas** mediante Group Policy.  
• Gestionar **altas, bajas y modificaciones** de cuentas.  
• Asignar **permisos NTFS y de red** basados en grupos.

---

## 📁 Estructura del dominio

```mermaid
graph TD
    A[lab.local] --> B[OU=Usuarios]
    B --> C[OU=Empleados]
    B --> D[OU=Personal]
    A --> E[OU=Grupos]
    A --> F[OU=Computadoras]
    A --> G[OU=Cuentas_Deshabilitadas]
```
---
## 📬 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ingrid-k)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ingridkaufmannok@gmail.com) 
