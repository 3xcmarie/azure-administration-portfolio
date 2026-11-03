# azure-administration-portfolio
Hands-on Microsoft Azure administration projects and technical documentation for AZ-104 preparation

# Azure Identity and Access Management Using RBAC

## 1. Project Overview

This project demonstrates how to configure and manage Role-Based Access Control (RBAC) in Microsoft Azure.

The goal is to implement secure access management by assigning appropriate permissions to users based on their responsibilities.

## 2. Project Objectives

- Understand Azure RBAC.
- Explore built-in Azure roles.
- Assign permissions at different scopes.
- Apply the principle of least privilege.
- Validate user access permissions.

## 3. Technologies Used

- Microsoft Azure
- Microsoft Entra ID
- Azure Role-Based Access Control (RBAC)
- Azure Resource Groups
- Azure Portal

## 4. Architecture

The project uses Azure RBAC to control access to resources.

Example:

- Subscription: Azure Subscription
- Resource Group: rg-iam-lab
- Role: Reader
- Scope: Resource Group

## 5. Implementation Steps

### Step 1: Create a Resource Group

1. Sign in to Azure Portal.
2. Navigate to Resource Groups.
3. Select Create.
4. Enter the resource group name: rg-iam-lab.
5. Select a region.
6. Review and create.

### Step 2: Navigate to Access Control (IAM)

1. Open the resource group.
2. Select Access Control (IAM).
3. Select Add role assignment.
4. Choose the Reader role.
5. Select the appropriate user or test identity.
6. Review and assign.

### Step 3: Validate Role Assignment

1. Open Access Control (IAM).
2. Navigate to Role Assignments.
3. Verify that the selected identity has the Reader role.
4. Review the assignment scope.

## 6. Screenshots

Add screenshots demonstrating:

- Resource group creation.
- Role assignment configuration.
- Access Control (IAM).
- Successful permission validation.

## 7. Testing and Validation

The role assignment was reviewed to verify that the selected identity received the intended permissions at the configured scope.

## 8. Security Considerations

- Follow the principle of least privilege.
- Avoid assigning unnecessary administrative permissions.
- Review role assignments regularly.
- Use Microsoft Entra ID identities for access management.

## 9. Lessons Learned

This project improved my understanding of Azure RBAC, permission management, role assignments, and access control scopes.

## 10. Conclusion

Successfully documented an Azure RBAC configuration exercise and demonstrated the fundamental concepts of identity and access management in Microsoft Azure.

**Note:** This is a personal learning lab, not a production deployment.
