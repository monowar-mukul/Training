# ☁️ AZ-104: Microsoft Azure Administrator
### Official Training Course Reference Guide

> **Exam:** AZ-104 · **Duration:** 4 Days Intensive · **Format:** Hands-On Labs + Lecture  
> **Labs:** 14 Real-World Exercises · **Certification:** Microsoft Certified: Azure Administrator Associate

[![Microsoft Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/en-us/certifications/azure-administrator/)
[![Exam AZ-104](https://img.shields.io/badge/Exam-AZ--104-003A75?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/certifications/exams/az-104/)
[![Labs](https://img.shields.io/badge/Hands--On_Labs-14_Exercises-00BCF2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator)

---

## 📋 Table of Contents

| # | Section | Click to Navigate |
|---|---------|-------------------|
| 1 | 🎯 Course Overview | [→ Jump](#-course-overview) |
| 2 | 👥 Who Should Attend | [→ Jump](#-who-should-attend) |
| 3 | ✅ Prerequisites | [→ Jump](#-prerequisites) |
| 4 | 🗺️ Module 01 — Manage Microsoft Entra ID Identities | [→ Jump](#-module-01--manage-microsoft-entra-id-identities) |
| 5 | 🏢 Module 02a — Manage Subscriptions & RBAC | [→ Jump](#-module-02a--manage-subscriptions--rbac) |
| 6 | 📋 Module 02b — Manage Governance via Azure Policy | [→ Jump](#-module-02b--manage-governance-via-azure-policy) |
| 7 | 📦 Module 03 — Manage Resources via ARM Templates | [→ Jump](#-module-03--manage-azure-resources-via-arm-templates) |
| 8 | 🌐 Module 04 — Implement Virtual Networking | [→ Jump](#-module-04--implement-virtual-networking) |
| 9 | 🔗 Module 05 — Implement Intersite Connectivity | [→ Jump](#-module-05--implement-intersite-connectivity) |
| 10 | ⚖️ Module 06 — Implement Network Traffic Management | [→ Jump](#-module-06--implement-network-traffic-management) |
| 11 | 💾 Module 07 — Manage Azure Storage | [→ Jump](#-module-07--manage-azure-storage) |
| 12 | 💻 Module 08 — Manage Virtual Machines | [→ Jump](#-module-08--manage-virtual-machines) |
| 13 | 🐳 Module 09 — Implement Web Apps & Containers | [→ Jump](#-module-09--implement-web-apps--containers) |
| 14 | 🛡️ Module 10 — Implement Data Protection | [→ Jump](#-module-10--implement-data-protection) |
| 15 | 📊 Module 11 — Implement Monitoring | [→ Jump](#-module-11--implement-monitoring) |
| 16 | 🏆 Learning Outcomes | [→ Jump](#-learning-outcomes) |
| 17 | 📅 4-Day Schedule | [→ Jump](#-4-day-training-schedule) |
| 18 | 🔗 Useful Resources | [→ Jump](#-useful-resources) |

---

## 🎯 Course Overview

**Microsoft Azure Administrator (AZ-104)** is one of the most in-demand cloud certifications globally. This course fast-tracks your expertise across every core Azure administration domain — giving you both the hands-on skills for real-world deployments and the knowledge to pass the AZ-104 exam with confidence.

### 💡 Why This Course?

| Benefit | Detail |
|---------|--------|
| 🏅 **Industry-Recognised** | Trusted by Fortune 500 companies and government agencies worldwide |
| 🔬 **100% Lab-Driven** | Every concept reinforced with a live Azure lab exercise |
| 📐 **End-to-End Coverage** | Identity → Governance → Networking → Storage → Compute → Monitoring |
| 👨‍🏫 **Expert-Led** | Microsoft Certified Trainer with real-world enterprise Azure experience |
| ⏱️ **4 Days Intensive** | Structured to achieve exam readiness efficiently without cutting corners |

> 💬 *"Azure Administrator is the gateway credential for cloud professionals. Earning it proves you can run Azure for real — not just describe it."*

[🔝 Back to Top](#-table-of-contents)

---

## 👥 Who Should Attend

This course is designed for professionals ready to take ownership of Azure infrastructure in production environments.

| Audience | Why This Course Fits |
|----------|----------------------|
| 👩‍💼 **IT Administrators** | Transitioning on-premises workloads to Azure or managing hybrid environments |
| ☁️ **Cloud Engineers** | Building and maintaining cloud-native infrastructure with automation-first practices |
| 🔒 **Security Professionals** | Implementing RBAC, Azure Policy, and network security controls across subscriptions |
| 🧑‍💻 **DevOps Engineers** | Deepening Azure infrastructure expertise alongside CI/CD practices |
| 📊 **Solutions Architects** | Validating administrator skills to complement cloud design work |

[🔝 Back to Top](#-table-of-contents)

---

## ✅ Prerequisites

Before attending, participants should have:

- **Operating System Knowledge** — Windows Server or Linux system administration concepts
- **Networking Fundamentals** — IP addressing, DNS, TCP/IP, and basic network security
- **Azure Awareness** — Familiarity with core Azure services (AZ-900 or equivalent is ideal)
- **Scripting Basics** — Exposure to PowerShell or Azure CLI (beneficial, not required)
- **Azure Subscription** — An active Azure subscription or lab environment for hands-on exercises

> ⚠️ **Note:** You may change the region for lab exercises, but all steps are written using **East US** as the default region.

[🔝 Back to Top](#-table-of-contents)

---

## 🗺️ Module 01 — Manage Microsoft Entra ID Identities

> **Lab 01** · ⏱️ Estimated Time: **30 minutes** · 📁 Theme: *Identity & Access*

### What You Will Learn

Users and groups are the foundational building blocks of every Azure identity solution. In this module you provision user accounts, invite external collaborators, and create groups with automatic dynamic membership — minimising administrative overhead from day one.

### 🏗️ Architecture Overview

```
┌─────────────────────────────────────────────┐
│                   Task 1                    │
│   User1 (IT Lab Admin)  +  Invited Guest    │
│              ↓                              │
│                   Task 2                    │
│          IT Lab Administrators Group        │
└─────────────────────────────────────────────┘
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Create and configure user accounts | Create `az104-user1`, set job title, department, usage location |
| **Task 1b** | Invite an external guest user | Send B2B invitation with welcome message |
| **Task 2** | Create groups and add members | Create Security group, add static members, explore dynamic rules |

### 🔑 Key Concepts

- A **tenant** represents your organisation — a specific instance of Microsoft Entra ID
- **User accounts** store name, department, location, job title, and contact information
- **Guest accounts** allow B2B collaboration via email invitation
- **Security groups** combine related users or devices; membership can be static or dynamic
- **Dynamic membership** updates automatically based on user properties (e.g., job title)
- **Entra ID Premium P1/P2** licence is required for dynamic group membership

### 💻 Quick Reference — PowerShell & CLI

```powershell
# Create a security group (PowerShell)
New-AzADGroup -DisplayName "IT Lab Administrators" -MailNickname "ITLabAdmins"

# Invite a guest user
New-AzADUser -DisplayName "Guest User" -UserPrincipalName "guest@external.com"
```

```bash
# Create a group (Azure CLI)
az ad group create --display-name "IT Lab Administrators" --mail-nickname "ITLabAdmins"
```

### ✅ Key Takeaways

- [ ] Tenants manage specific Microsoft cloud service instances for internal and external users
- [ ] Each account has a level of access specific to its expected scope of work
- [ ] Groups of type **Security** and **Microsoft 365** serve different collaboration purposes
- [ ] Group membership can be **statically** or **dynamically** assigned

[🔝 Back to Top](#-table-of-contents)

---

## 🏢 Module 02a — Manage Subscriptions & RBAC

> **Lab 02a** · ⏱️ Estimated Time: **20 minutes** · 📁 Theme: *Governance & Access Control*

### What You Will Learn

Role-Based Access Control (RBAC) controls what identities can and cannot do across Azure resources. This module shows you how to organise subscriptions into management groups, assign built-in roles, create custom roles following the principle of least privilege, and audit role changes through the Activity Log.

### 🏗️ Architecture Overview

```
az104-mg1 (Management Group)
    ├── Task 2: Built-in Role → Virtual Machine Contributor → Help Desk Group
    ├── Task 3: Custom Role  → Custom Support Request → Help Desk Group
    └── Task 4: Activity Log → Monitor role assignment changes
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Implement Management Groups | Create `az104-mg1`, understand root management group hierarchy |
| **Task 2** | Review and assign a built-in Azure role | Assign **Virtual Machine Contributor** to Help Desk group |
| **Task 3** | Create a custom RBAC role | Clone **Support Request Contributor**, remove provider registration permission |
| **Task 4** | Monitor role assignments with Activity Log | Filter Activity Log for role assignment operations |

### 🔑 Key Concepts

- **Management groups** logically organise subscriptions and allow inherited RBAC/Policy
- The **root management group** sits at the top of every Azure hierarchy
- **Built-in roles** — Owner, Contributor, Reader are the most commonly used
- **Custom roles** defined in JSON with `Actions`, `NotActions`, and `AssignableScopes`
- **Principle of least privilege** — assign only the permissions genuinely needed
- Always assign roles to **groups**, not to individual users

### 💻 Quick Reference — PowerShell & CLI

```powershell
# Create a management group
New-AzManagementGroup -GroupName "az104-mg1" -DisplayName "az104-mg1"

# Assign a built-in role
New-AzRoleAssignment -ObjectId <GroupObjectId> `
  -RoleDefinitionName "Virtual Machine Contributor" `
  -Scope "/providers/Microsoft.Management/managementGroups/az104-mg1"

# Remove management group (cleanup)
Remove-AzManagementGroup -GroupName az104-mg1
```

```bash
# Delete management group (Azure CLI)
az account management-group delete --name az104-mg1
```

### 📄 Custom Role JSON Structure

```json
{
  "Name": "Custom Support Request",
  "Description": "A custom contributor role for support requests.",
  "Actions": ["Microsoft.Support/*", "Microsoft.Compute/*"],
  "NotActions": ["Microsoft.Support/register/action"],
  "AssignableScopes": ["/providers/Microsoft.Management/managementGroups/az104-mg1"]
}
```

### ✅ Key Takeaways

- [ ] Management groups logically organise subscriptions across the enterprise
- [ ] Azure has many built-in roles — assign these before creating custom ones
- [ ] Custom roles can be created by cloning built-ins and removing unnecessary permissions
- [ ] Roles are defined in JSON with `Actions`, `NotActions`, and `AssignableScopes`
- [ ] Use the Activity Log to monitor and audit all role assignment changes

[🔝 Back to Top](#-table-of-contents)

---

## 📋 Module 02b — Manage Governance via Azure Policy

> **Lab 02b** · ⏱️ Estimated Time: **30 minutes** · 📁 Theme: *Governance & Compliance*

### What You Will Learn

Azure Policy enforces organisational standards and assesses compliance at scale. This module covers resource tagging, policy assignment, automated remediation of non-compliant resources, and resource locks that prevent accidental deletion.

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Assign tags via the Azure portal | Create resource group `az104-rg2` with tag `Cost Center: 000` |
| **Task 2** | Enforce tagging via Azure Policy | Assign built-in *Require a tag and its value* policy — test denial |
| **Task 3** | Apply tagging via Azure Policy | Assign *Inherit a tag from resource group* with remediation task |
| **Task 4** | Configure and test resource locks | Create Delete lock `rg-lock` — verify deletion is blocked |

### 🔑 Key Concepts

- **Resource tags** are key-value metadata pairs for identifying resource owners, cost centres, environments
- **Azure Policy** enforces configuration rules — deny, audit, or modify non-compliant resources
- **Policy effects:** `Deny`, `Audit`, `Modify`, `DeployIfNotExists`, `AuditIfNotExists`
- **Remediation tasks** bring existing non-compliant resources into compliance
- **Resource locks** — `ReadOnly` or `Delete` — override all user permissions
- **Azure Policy** = pre-deployment security; **RBAC + Locks** = post-deployment security

### 💻 Quick Reference — PowerShell & CLI

```powershell
# Add a resource lock
New-AzResourceLock -LockName "rg-lock" -LockLevel CanNotDelete `
  -ResourceGroupName "az104-rg2"

# Remove a resource group (cleanup — remove lock first)
Remove-AzResourceGroup -Name resourceGroupName
```

```bash
# Add resource lock (Azure CLI)
az lock create --name rg-lock --lock-type CanNotDelete \
  --resource-group az104-rg2

# Delete resource group
az group delete --name resourceGroupName
```

### ✅ Key Takeaways

- [ ] Tags are key-value metadata — critical for cost management and governance reporting
- [ ] Policy definitions describe resource compliance conditions and the effect to take
- [ ] Remediation tasks fix existing non-compliant `Modify` or `DeployIfNotExists` resources
- [ ] Resource locks protect against accidental deletion or modification — they override user permissions
- [ ] Policy is pre-deployment governance; resource locks are post-deployment protection

[🔝 Back to Top](#-table-of-contents)

---

## 📦 Module 03 — Manage Azure Resources via ARM Templates

> **Lab 03** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Infrastructure as Code*

### What You Will Learn

Eliminate manual deployments and human error. This module covers creating, exporting, editing, and deploying Azure Resource Manager templates and Bicep files — using the portal, Azure PowerShell, the Azure CLI, and Azure Cloud Shell.

### 🏗️ Architecture Overview

```
Disk 1 (Portal) → Export JSON Template
    ├── Task 2: Edit + Redeploy → Disk 2 (Portal)
    ├── Task 3: PowerShell     → Disk 3 (Cloud Shell)
    ├── Task 4: CLI            → Disk 4 (Cloud Shell)
    └── Task 5: Bicep          → Disk 5 (Cloud Shell)
```

### 📝 Lab Tasks

| Task | Description | Tool |
|------|-------------|------|
| **Task 1** | Create an ARM template from existing resource | Azure Portal |
| **Task 2** | Edit template and redeploy | Azure Portal — Custom Deployment |
| **Task 3** | Deploy template with PowerShell | Azure Cloud Shell — PowerShell |
| **Task 4** | Deploy template with CLI | Azure Cloud Shell — Bash |
| **Task 5** | Deploy resource using Azure Bicep | Azure Cloud Shell — Bash |

### 🔑 Key Concepts

- **ARM templates** are JSON files enabling declarative infrastructure management
- **Parameters files** separate environment-specific values from the template structure
- **Bicep** is a domain-specific language that compiles to ARM JSON — more concise and readable
- **Cloud Shell** is a browser-accessible authenticated terminal (PowerShell or Bash)
- Template deployments can target **resource group**, **subscription**, **management group**, or **tenant**

### 💻 Quick Reference — PowerShell & CLI

```powershell
# Deploy ARM template with PowerShell
New-AzResourceGroupDeployment `
  -ResourceGroupName az104-rg3 `
  -TemplateFile template.json `
  -TemplateParameterFile parameters.json

# Verify disks created
Get-AzDisk | ft Name, ResourceGroupName, Location, DiskSizeGb, ProvisioningState
```

```bash
# Deploy ARM template with CLI
az deployment group create \
  --resource-group az104-rg3 \
  --template-file template.json \
  --parameters parameters.json

# Deploy Bicep file
az deployment group create \
  --resource-group az104-rg3 \
  --template-file azuredeploydisk.bicep

# List created disks
az disk list --resource-group az104-rg3 --output table
```

### ✅ Key Takeaways

- [ ] ARM templates deploy all resources for a solution as a group, not individually
- [ ] ARM templates are JSON — they define infrastructure **declaratively** rather than with scripts
- [ ] Use a separate parameters JSON file to avoid hardcoding values
- [ ] Bicep is the modern alternative — concise syntax, reliable type safety, code reuse
- [ ] Templates can be deployed via Portal, PowerShell, CLI, and Cloud Shell

[🔝 Back to Top](#-table-of-contents)

---

## 🌐 Module 04 — Implement Virtual Networking

> **Lab 04** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Networking Foundations*

### What You Will Learn

Design and deploy virtual networks, subnets, and DNS zones that form the backbone of every Azure workload. This module covers NSG and ASG configuration for network security, plus both public and private Azure DNS zone management.

### 🏗️ Architecture Overview

```
az104-rg4
├── CoreServicesVnet (10.20.0.0/16)
│   ├── SharedServicesSubnet (10.20.10.0/24)
│   └── DatabaseSubnet (10.20.20.0/24)
├── ManufacturingVnet (10.30.0.0/16)
│   ├── SensorSubnet1 (10.30.20.0/24)
│   └── SensorSubnet2 (10.30.21.0/24)
├── NSG: myNSGSecure → SharedServicesSubnet
├── ASG: asg-web
├── DNS Public Zone:  contoso.com
└── DNS Private Zone: private.contoso.com
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Create VNet with subnets via portal | Create `CoreServicesVnet` with 2 subnets |
| **Task 2** | Create VNet and subnets via template | Deploy `ManufacturingVnet` from exported JSON template |
| **Task 3** | Create and configure ASG + NSG | Allow ASG traffic inbound (port 80/443), deny internet outbound |
| **Task 4** | Configure public and private DNS zones | Create `contoso.com` public zone + `private.contoso.com` private zone |

### 🔑 Key Concepts

- **Virtual Network (VNet)** — your own private network in Azure cloud
- Avoid overlapping IP address ranges across VNets and on-premises networks
- Every VNet needs **at least one subnet**; five IP addresses per subnet are always reserved
- **NSG** (Network Security Group) — contains inbound/outbound security rules; default rules exist
- **ASG** (Application Security Group) — groups servers by function (web servers, DB servers)
- **Public DNS zones** — resolve host names in your public domain
- **Private DNS zones** — provide name resolution within virtual networks only

### 💻 Quick Reference

```bash
# Create a VNet with CLI
az network vnet create \
  --resource-group az104-rg4 \
  --name CoreServicesVnet \
  --address-prefix 10.20.0.0/16 \
  --subnet-name SharedServicesSubnet \
  --subnet-prefix 10.20.10.0/24

# Test DNS resolution
nslookup www.contoso.com <nameserver-from-portal>
```

### ✅ Key Takeaways

- [ ] Avoid overlapping IP ranges — it causes routing and troubleshooting issues
- [ ] Subnets divide a VNet for organisation and security — five IPs always reserved per subnet
- [ ] NSGs contain inbound/outbound rules — default rules can be customised but not deleted
- [ ] ASGs protect groups of servers sharing a common function (web, database, etc.)
- [ ] Azure DNS can host public domains and provide private resolution within VNets

[🔝 Back to Top](#-table-of-contents)

---

## 🔗 Module 05 — Implement Intersite Connectivity

> **Lab 05** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Network Connectivity*

### What You Will Learn

Connect separate virtual networks securely. This module covers VNet peering, connection testing with Network Watcher, and creating user-defined routes to control traffic flow through virtual network appliances.

### 🏗️ Architecture Overview

```
CoreServicesVnet (10.0.0.0/16)          ManufacturingVnet (172.16.0.0/16)
├── Core Subnet (10.0.0.0/24)     ◄────►  Manufacturing Subnet (172.16.0.0/24)
│   └── CoreServicesVM                        └── ManufacturingVM
├── Perimeter Subnet (10.0.1.0/24)
└── Route Table: rt-CoreServices
    └── Route: PerimetertoCore → NVA (10.0.1.7)
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Create CoreServicesVM and VNet | Deploy VM with new VNet `CoreServicesVnet` |
| **Task 2** | Create ManufacturingVM in separate VNet | Deploy VM with `ManufacturingVnet` |
| **Task 3** | Test connection with Network Watcher | Run Connection Troubleshoot — expect **Unreachable** |
| **Task 4** | Configure VNet peering | Create bidirectional peering — retest shows **Reachable** |
| **Task 5** | Test with Azure PowerShell | Run `Test-NetConnection` from ManufacturingVM |
| **Task 6** | Create a custom route | Create route table, add NVA route, associate with Perimeter subnet |

### 🔑 Key Concepts

- By default, resources in **different VNets cannot communicate**
- **VNet peering** connects two or more VNets — peered VNets appear as one for connectivity
- Traffic between peered VMs uses the **Microsoft backbone** infrastructure (not public internet)
- **System routes** are created automatically; **user-defined routes (UDR)** override defaults
- **Network Watcher** provides tools to monitor, diagnose, and view metrics for Azure IaaS resources

### 💻 Quick Reference — PowerShell

```powershell
# Test connection from ManufacturingVM (Run Command)
Test-NetConnection <CoreServicesVM-Private-IP> -port 3389

# Add VNet peering with PowerShell
Add-AzVirtualNetworkPeering `
  -Name "CoreToManufacturing" `
  -VirtualNetwork $coreVnet `
  -RemoteVirtualNetworkId $mfgVnet.Id
```

### ✅ Key Takeaways

- [ ] Resources in different VNets cannot communicate by default — peering is required
- [ ] VNet peering is non-transitive — A↔B and B↔C does **not** mean A↔C
- [ ] Peered VNet traffic uses Microsoft backbone — fast, private, and low latency
- [ ] User-defined routes (UDRs) override system routes for traffic steering
- [ ] Network Watcher's Connection Troubleshoot is your first diagnostic tool

[🔝 Back to Top](#-table-of-contents)

---

## ⚖️ Module 06 — Implement Network Traffic Management

> **Lab 06** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Load Balancing & Application Delivery*

### What You Will Learn

Distribute traffic intelligently across your workloads. This module implements both an Azure Load Balancer (Layer 4) for VM traffic distribution and an Azure Application Gateway (Layer 7) for URL path-based routing to different backend pools.

### 🏗️ Architecture Overview

```
Internet Traffic
    │
    ├── Azure Load Balancer (Layer 4 - TCP/UDP)
    │   ├── Frontend IP: az104-lbpip
    │   ├── Backend Pool: az104-06-vm0 + az104-06-vm1
    │   └── Rule: Port 80 → Health Probe → Round Robin
    │
    └── Azure Application Gateway (Layer 7 - HTTP/HTTPS)
        ├── Frontend IP: az104-gwpip
        ├── Backend Pool (default): az104-06-vm1 + az104-06-vm2
        ├── Route /image/* → az104-imagebe (vm1)
        └── Route /video/* → az104-videobe (vm2)
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Provision infrastructure via template | Deploy VNet, NSG, and 3 VMs from template |
| **Task 2** | Configure Azure Load Balancer | Create `az104-lb`, backend pool, health probe, and LB rule on port 80 |
| **Task 3** | Configure Azure Application Gateway | Create `az104-appgw`, path-based routing for `/image/*` and `/video/*` |

### 🔑 Key Concepts

- **Azure Load Balancer** — OSI Layer 4 (TCP/UDP), distributes within the same VNet
- **Standard SKU** Load Balancer provides static IP, zone redundancy, and enhanced metrics
- **Health probes** determine if backend instances are healthy before sending traffic
- **Application Gateway** — OSI Layer 7 (HTTP/HTTPS), enables WAF, SSL termination, path-based routing
- **WAF tier** adds Web Application Firewall on top of Application Gateway Standard features
- Application Gateway requires a **dedicated subnet** of `/27` or larger

### 💻 Quick Reference

```bash
# Test Load Balancer (open browser to frontend IP)
curl http://<frontend-public-ip>
# Expected: "Hello World from az104-06-vm0" or "az104-06-vm1"

# Test Application Gateway path routing
curl http://<appgw-public-ip>/image/
# Expected: served from vm1

curl http://<appgw-public-ip>/video/
# Expected: served from vm2
```

### ✅ Key Takeaways

- [ ] Load Balancer is OSI Layer 4 — best for TCP/UDP VM traffic distribution
- [ ] Application Gateway is OSI Layer 7 — enables URL/path-based routing and WAF
- [ ] Standard Load Balancer supports zone redundancy; Basic does not
- [ ] Application Gateway needs a dedicated `/27` or larger subnet
- [ ] WAF tier adds protection against common web exploits (OWASP ruleset)

[🔝 Back to Top](#-table-of-contents)

---

## 💾 Module 07 — Manage Azure Storage

> **Lab 07** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Storage Management*

### What You Will Learn

Create and secure Azure storage for blobs, files, and structured data. This module covers redundancy options, lifecycle management policies, blob container security, SAS token generation, Azure File shares, and network-level access restrictions.

### 🏗️ Architecture Overview

```
Storage Account (az104-07-rg7)
├── Task 1: Storage Account
│   ├── Redundancy: GRS (Geo-Redundant Storage)
│   ├── Public Access: Selected Networks only
│   └── Lifecycle Rule: Move to Cool after 30 days
├── Task 2: Blob Container
│   ├── Container: data (Private access)
│   ├── Immutability Policy: 180 days time-based retention
│   └── SAS Token: Read-only, 24-hour expiry
└── Task 3: Azure File Share
    ├── Share: share1 (Transaction Optimized)
    └── Network Restriction: vnet1 (service endpoint)
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Create and configure a storage account | GRS redundancy, disable public access, add lifecycle rule |
| **Task 2** | Create and configure secure blob storage | Create container, set immutability policy, generate SAS token |
| **Task 3** | Create and configure Azure File storage | Create file share, upload via Storage Browser, restrict to VNet |

### 🔑 Key Concepts

- **Storage redundancy options:** LRS → ZRS → GRS → GZRS (increasing resilience)
- **Blob storage** — unstructured data (images, videos, backups, logs)
- **Azure Files** — fully managed file shares accessible via SMB and NFS
- **Immutable storage** — Write Once, Read Many (WORM) using time-based or legal-hold policies
- **SAS (Shared Access Signature)** — grant limited, time-bound access to storage resources
- **Lifecycle management** — automate tiering from Hot → Cool → Archive → Delete
- **Service endpoints** restrict storage access to specific VNet subnets

### 💻 Quick Reference — PowerShell

```powershell
# Create a storage account
New-AzStorageAccount `
  -ResourceGroupName az104-rg7 `
  -Name "mystorageaccount" `
  -Location "EastUS" `
  -SkuName "Standard_GRS" `
  -Kind "StorageV2"

# Generate a SAS token
$ctx = New-AzStorageContext -StorageAccountName "mystorageaccount" -StorageAccountKey "<key>"
New-AzStorageBlobSASToken -Container "data" -Blob "file.csv" `
  -Permission r -ExpiryTime (Get-Date).AddHours(24) -Context $ctx
```

### ✅ Key Takeaways

- [ ] Storage accounts provide a unique namespace for blobs, files, queues, and tables
- [ ] Choose redundancy based on your RPO requirements — GRS replicates to a secondary region
- [ ] Blob immutability policies enforce WORM compliance for regulated data
- [ ] SAS tokens grant time-limited, permission-scoped access without sharing account keys
- [ ] Service endpoints restrict storage access to approved VNet subnets only

[🔝 Back to Top](#-table-of-contents)

---

## 💻 Module 08 — Manage Virtual Machines

> **Lab 08** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Compute Management*

### What You Will Learn

Deploy, scale, and manage Azure virtual machines for production workloads. This module covers zone-resilient VM deployment, vertical and horizontal scaling, VM Scale Sets with custom autoscale rules, and VM creation via both PowerShell and CLI.

### 🏗️ Architecture Overview

```
az104-rg8
├── Task 1 & 2: Zone-Resilient VMs
│   ├── az104-vm1 (Zone 1) — Premium SSD, Standard_D2s_v3
│   └── az104-vm2 (Zone 2) — Premium SSD, Standard_D2s_v3
│       └── Task 2: Resize to D2ds_v4, attach/detach data disk
└── Tasks 3 & 4: VM Scale Set
    ├── vmss1 (Zones 1, 2, 3) — Uniform orchestration
    ├── Autoscale OUT: CPU > 70% for 10 min → +50% instances
    ├── Autoscale IN:  CPU < 30% for 10 min → -50% instances
    └── Limits: Min=2, Max=10, Default=2
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Deploy zone-resilient VMs | Create 2 VMs across Zone 1 and Zone 2 |
| **Task 2** | Manage compute and storage scaling | Resize VM SKU, create/attach/detach data disk, change storage type |
| **Task 3** | Create Azure VM Scale Set | Deploy `vmss1` across 3 zones with NSG, load balancer, and public IP |
| **Task 4** | Configure custom autoscale rules | Set scale-out (CPU>70%) and scale-in (CPU<30%) rules with instance limits |
| **Task 5** | Create VM with Azure PowerShell *(optional)* | Deploy VM using `New-AzVm` cmdlet |
| **Task 6** | Create VM with Azure CLI *(optional)* | Deploy Ubuntu VM using `az vm create` |

### 🔑 Key Concepts

- **Availability Zones** provide 99.99% uptime SLA — deploy across at least 2 zones
- **Vertical scaling** — resize VM SKU (more CPU/RAM); requires VM restart
- **Horizontal scaling** — add/remove VM instances; no restart required
- **VM Scale Sets** automate horizontal scaling based on metrics or schedules
- **Uniform orchestration** — identical VM instances; best for stateless workloads
- `Deallocated` state = VM stopped + compute billing stopped (storage still billed)

### 💻 Quick Reference — PowerShell & CLI

```powershell
# Create VM with PowerShell
New-AzVm `
  -ResourceGroupName 'az104-rg8' `
  -Name 'myPSVM' `
  -Location 'East US' `
  -Image 'Win2019Datacenter' `
  -Zone '1' `
  -Size 'Standard_D2s_v3' `
  -Credential (Get-Credential)

# Deallocate VM
Stop-AzVM -ResourceGroupName 'az104-rg8' -Name 'myPSVM'
```

```bash
# Create Linux VM with CLI
az vm create \
  --name myCLIVM \
  --resource-group az104-rg8 \
  --image Ubuntu2204 \
  --admin-username localadmin \
  --generate-ssh-keys

# Deallocate VM
az vm deallocate --resource-group az104-rg8 --name myCLIVM
```

### ✅ Key Takeaways

- [ ] Deploy VMs across availability zones for 99.99% uptime SLA
- [ ] VMs support both vertical (resize SKU) and horizontal (add instances) scaling
- [ ] VM Scale Sets create and manage a group of load-balanced, identical VMs
- [ ] Deallocated VMs stop compute billing — static public IPs are released
- [ ] Autoscale rules should have both scale-out AND scale-in rules with instance limits

[🔝 Back to Top](#-table-of-contents)

---

## 🐳 Module 09 — Implement Web Apps & Containers

> **Labs 09a / 09b / 09c** · ⏱️ Estimated Time: **50 minutes total** · 📁 Theme: *PaaS & Containers*

### What You Will Learn

Move beyond VMs into Platform-as-a-Service and containerised workloads. This module covers Azure App Service web apps with deployment slots and autoscaling, Azure Container Instances for short-lived workloads, and Azure Container Apps for serverless microservices.

### 🏗️ Architecture Overview

```
Lab 09a — Azure App Service
├── Production Slot  ←── Swap ──┐
├── Staging Slot (GitHub deploy)┘
└── Autoscale: Automatic, Max burst = 2

Lab 09b — Azure Container Instances
└── az104-c1 (mcr.microsoft.com/azuredocs/aci-helloworld)
    └── Public FQDN → Port 80

Lab 09c — Azure Container Apps
└── my-app (Simple hello world container)
    └── my-environment → Application URL
```

### 📝 Lab Tasks

| Lab | Task | Description |
|-----|------|-------------|
| **09a** | Task 1 | Create App Service web app (PHP 8.2, Linux, Premium V3 P1V3) |
| **09a** | Task 2 | Create staging deployment slot |
| **09a** | Task 3 | Configure GitHub external git deployment to staging slot |
| **09a** | Task 4 | Swap staging slot to production |
| **09a** | Task 5 | Configure autoscaling with load test |
| **09b** | Task 1 | Deploy Azure Container Instance using Docker image |
| **09b** | Task 2 | Test and verify ACI deployment via FQDN |
| **09c** | Task 1 | Create Azure Container App and environment |
| **09c** | Task 2 | Test and verify Container App deployment |

### 🔑 Key Concepts

- **Azure App Service** is PaaS — supports PHP, Java, .NET, Python, Node.js without managing servers
- **Deployment slots** enable blue-green deployments — test in staging, swap to production instantly
- **App Service Plan** determines compute, storage, and features available to the web app
- **Azure Container Instances (ACI)** — serverless containers for short-lived tasks, no infrastructure management
- **Azure Container Apps (ACA)** — serverless platform for long-running microservices and APIs built on Kubernetes
- **ACA vs ACI:** ACA is for long-running apps (web, APIs); ACI is for short-lived burst workloads

### 💻 Quick Reference — CLI

```bash
# Create App Service Plan
az appservice plan create \
  --name myAppServicePlan \
  --resource-group az104-rg9 \
  --sku P1V3 --is-linux

# Create Web App
az webapp create \
  --resource-group az104-rg9 \
  --plan myAppServicePlan \
  --name myUniqueWebApp \
  --runtime "PHP:8.2"

# Deploy Container Instance
az container create \
  --resource-group az104-rg9 \
  --name az104-c1 \
  --image mcr.microsoft.com/azuredocs/aci-helloworld \
  --dns-name-label myuniquedns \
  --ports 80
```

### ✅ Key Takeaways

- [ ] App Service is PaaS — no OS patching, no infrastructure management required
- [ ] Deployment slots enable zero-downtime deployments via slot swap
- [ ] ACI is ideal for short-lived burst workloads — billed per second, no idle cost
- [ ] ACA removes Kubernetes cluster management complexity for microservices teams
- [ ] Autoscaling keeps performance optimal when traffic to a web app increases

[🔝 Back to Top](#-table-of-contents)

---

## 🛡️ Module 10 — Implement Data Protection

> **Lab 10** · ⏱️ Estimated Time: **50 minutes** · 📁 Theme: *Backup & Disaster Recovery*

### What You Will Learn

Protect Azure virtual machines from data loss and regional outages. This module covers Recovery Services vault creation, backup policy configuration, backup monitoring with diagnostic settings, and VM replication to a secondary region using Azure Site Recovery.

### 🏗️ Architecture Overview

```
Region 1 (East US)                    Region 2 (West US)
az104-rg-region1                      az104-rg-region2
├── az104-10-vm0  ──── replication ──► az104-rsv-region2
├── az104-rsv-region1                      └── Replicated Items
│   ├── Backup Policy: az104-backup              └── az104-10-vm0
│   │   ├── Frequency: Daily 12:00 AM                 Status: Healthy
│   │   └── Retention: 30 days
│   └── Diagnostic Settings → Storage Account
└── Monitor → Backup Jobs
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Provision infrastructure via template | Deploy VM `az104-10-vm0` in East US |
| **Task 2** | Create Recovery Services vault | Create `az104-rsv-region1`, review geo-redundant storage and soft delete |
| **Task 3** | Configure VM-level backup | Create backup policy `az104-backup`, enable backup for vm0 |
| **Task 4** | Monitor Azure Backup | Configure diagnostic settings → storage account, review backup jobs |
| **Task 5** | Enable VM replication | Create vault in West US, enable ASR replication from East US to West US |

### 🔑 Key Concepts

- **Recovery Services vault** stores backup data and replication configuration
- **Backup policies** define frequency (daily/weekly) and retention period
- **Enhanced** vs **Standard** policy sub-types — Enhanced supports hourly backups
- **Soft delete** — backup data retained for 14 days after deletion (protection against accidental loss)
- **Azure Site Recovery (ASR)** replicates workloads to secondary region for disaster recovery
- **RPO** (Recovery Point Objective) and **RTO** (Recovery Time Objective) drive your DR strategy

### 💻 Quick Reference — PowerShell & CLI

```powershell
# Get backup job status
Get-AzRecoveryServicesBackupJob -VaultId $vault.ID

# Trigger an on-demand backup
Backup-AzRecoveryServicesBackupItem `
  -Item $backupItem `
  -VaultId $vault.ID
```

```bash
# Check backup job status (Azure CLI)
az backup job list \
  --resource-group az104-rg-region1 \
  --vault-name az104-rsv-region1 \
  --output table
```

> ⚠️ **Cleanup Note:** To delete a Recovery Services vault you must first remove all protected items, disable soft delete, and remove backup infrastructure before deleting the vault itself.

### ✅ Key Takeaways

- [ ] Azure Backup provides simple, secure, cost-effective backup for VMs and file shares
- [ ] Backup policies control frequency and retention — different VMs can have different policies
- [ ] Soft delete retains backup data 14 days after deletion, protecting against accidents
- [ ] Azure Site Recovery replicates VMs to a secondary region for disaster recovery failover
- [ ] A Recovery Services vault stores both backup data and ASR replication configuration

[🔝 Back to Top](#-table-of-contents)

---

## 📊 Module 11 — Implement Monitoring

> **Lab 11** · ⏱️ Estimated Time: **40 minutes** · 📁 Theme: *Operations & Observability*

### What You Will Learn

Gain complete operational visibility into your Azure environment. This module covers Azure Monitor alert creation, action group configuration for email notifications, alert triggering and validation, alert processing rules for maintenance windows, and Log Analytics KQL queries.

### 🏗️ Architecture Overview

```
az104-rg11
├── az104-11-vm0
│   └── VM Insights enabled → Log Analytics Workspace
├── Azure Monitor
│   ├── Task 2: Alert Rule "VM was deleted" (Activity Log signal)
│   ├── Task 3: Action Group "AlertOpsTeam" → Email notification
│   ├── Task 4: Delete vm0 → Alert fires → Email received
│   ├── Task 5: Alert Processing Rule "Planned Maintenance"
│   │           └── Suppress notifications 10pm → 7am
│   └── Task 6: Log Analytics KQL Queries
│               ├── Count heartbeats
│               └── CPU utilisation timechart
└── Activity Log → Audit trail of all operations
```

### 📝 Lab Tasks

| Task | Description | Key Actions |
|------|-------------|-------------|
| **Task 1** | Provision infrastructure + configure VM Insights | Deploy VM, enable Azure Monitor for VMs |
| **Task 2** | Create an alert rule | Alert on "Delete Virtual Machine" Activity Log signal — subscription scope |
| **Task 3** | Configure action group notifications | Create `AlertOpsTeam` action group with email notification |
| **Task 4** | Trigger alert and confirm it works | Delete `az104-vm0` — verify alert email received |
| **Task 5** | Configure alert processing rule | Create `Planned Maintenance` suppression rule (10pm–7am) |
| **Task 6** | Use Azure Monitor log queries | Run KQL heartbeat count + CPU utilisation timechart queries |

### 🔑 Key Concepts

- **Azure Monitor** is the unified platform for metrics, logs, alerts, and insights across all Azure resources
- **Alert rules** monitor data and capture signals — trigger when conditions are met
- **Action groups** define who gets notified (email, SMS, push, voice, webhook, Logic App)
- **Alert processing rules** suppress, add action groups, or modify alerts on a schedule
- **Log Analytics** uses **KQL (Kusto Query Language)** to query logs and metrics
- **VM Insights** automatically collects performance counters and maps dependencies

### 💻 KQL Query Reference

```kql
-- Count VM heartbeats (past hour)
Heartbeat
| where TimeGenerated > ago(1h)
| summarize count() by Computer

-- CPU utilisation timechart (VM Insights)
InsightsMetrics
| where TimeGenerated > ago(1h)
| where Name == "UtilizationPercentage"
| summarize avg(Val) by bin(TimeGenerated, 5m), Computer
| render timechart

-- Activity Log — filter for VM delete operations
AzureActivity
| where OperationNameValue == "Microsoft.Compute/virtualMachines/delete"
| project TimeGenerated, Caller, ResourceGroup, ActivityStatusValue
```

### ✅ Key Takeaways

- [ ] Azure Monitor alerts detect issues before users notice — proactive operations management
- [ ] Alert on any metric or log data source in the Azure Monitor data platform
- [ ] Action groups define notification channels — add individuals via groups, not directly
- [ ] Alert processing rules manage alert behaviour during planned maintenance windows
- [ ] KQL is the query language for Log Analytics — powerful for time-series analysis

[🔝 Back to Top](#-table-of-contents)

---

## 🏆 Learning Outcomes

By completing all 11 modules and 14 lab exercises, you will be able to:

| Domain | Skill |
|--------|-------|
| **Identity** | ✅ Create and manage users, groups, and guest accounts in Microsoft Entra ID |
| **Governance** | ✅ Implement management groups, RBAC roles, Azure Policy, tags, and resource locks |
| **Automation** | ✅ Deploy infrastructure using ARM templates, Bicep, PowerShell, and Azure CLI |
| **Networking** | ✅ Design VNets, subnets, NSGs, peerings, DNS zones, and custom route tables |
| **Load Balancing** | ✅ Configure Azure Load Balancer (L4) and Application Gateway (L7) with path routing |
| **Storage** | ✅ Create geo-redundant storage accounts with lifecycle policies and SAS tokens |
| **Compute** | ✅ Deploy zone-resilient VMs and VM Scale Sets with custom autoscale rules |
| **Containers** | ✅ Host workloads using App Service, Azure Container Instances, and Container Apps |
| **Protection** | ✅ Configure Azure Backup policies and Azure Site Recovery replication |
| **Monitoring** | ✅ Set up Azure Monitor alerts, action groups, and write KQL log queries |

[🔝 Back to Top](#-table-of-contents)

---

## 📅 4-Day Training Schedule

| Day | Theme | Modules | Labs |
|-----|-------|---------|------|
| **Day 1** | Identity & Governance | Modules 01, 02a, 02b | Labs 01, 02a, 02b |
| **Day 2** | Networking Foundations | Modules 03, 04, 05 | Labs 03, 04, 05 |
| **Day 3** | Compute, Storage & Apps | Modules 06, 07, 08, 09 | Labs 06, 07, 08, 09a–c |
| **Day 4** | Protection, Monitoring & Exam Prep | Modules 10, 11 + Review | Labs 10, 11 + Q&A |

> 💡 **Tip:** Each day builds on the previous. Networking concepts from Day 2 are applied in the storage and compute labs on Day 3.

[🔝 Back to Top](#-table-of-contents)

---

## 🔗 Useful Resources

### 📚 Official Microsoft Documentation

| Resource | Link |
|----------|------|
| AZ-104 Exam Page | [learn.microsoft.com/certifications/exams/az-104](https://learn.microsoft.com/en-us/certifications/exams/az-104/) |
| AZ-104 Study Guide | [Official Study Guide](https://learn.microsoft.com/en-us/certifications/resources/study-guides/az-104) |
| Microsoft Learn Path | [Azure Administrator Learning Path](https://learn.microsoft.com/en-us/training/paths/az-104-administrator-prerequisites/) |
| Lab GitHub Repository | [MicrosoftLearning/AZ-104](https://github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator) |

### 🛠️ Tools & Portals

| Tool | URL |
|------|-----|
| Azure Portal | [portal.azure.com](https://portal.azure.com) |
| Azure Cloud Shell | [shell.azure.com](https://shell.azure.com) |
| Microsoft Entra ID | [entra.microsoft.com](https://entra.microsoft.com) |
| Azure Monitor | [portal.azure.com/#blade/Microsoft_Azure_Monitoring](https://portal.azure.com) |

### 📖 Self-Paced Training Modules

| Module | Topic |
|--------|-------|
| [Understand Microsoft Entra ID](https://learn.microsoft.com/en-us/training/modules/understand-azure-active-directory/) | Identity fundamentals |
| [Secure resources with Azure RBAC](https://learn.microsoft.com/en-us/training/modules/secure-azure-resources-with-rbac/) | Role-based access control |
| [Azure Policy Initiatives](https://learn.microsoft.com/en-us/training/modules/build-cloud-governance-strategy-azure/) | Governance at scale |
| [Deploy ARM templates](https://learn.microsoft.com/en-us/training/modules/deploy-azure-infrastructure-by-using-json-arm-templates/) | Infrastructure as code |
| [Introduction to Azure VNets](https://learn.microsoft.com/en-us/training/modules/introduction-to-azure-virtual-networks/) | Virtual networking |
| [Azure Load Balancer](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-load-balancer/) | Traffic distribution |
| [Azure Blob Storage lifecycle](https://learn.microsoft.com/en-us/training/modules/manage-azure-blob-storage-lifecycle/) | Storage management |
| [Introduction to Azure VMs](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-virtual-machines/) | Virtual machines |
| [Azure Backup](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-backup/) | Data protection |
| [Azure Monitor alerts](https://learn.microsoft.com/en-us/training/modules/configure-azure-alerts/) | Monitoring & alerting |

---

## 📌 Quick Reference Card

```
AZ-104 EXAM DOMAINS                    WEIGHT
├── Manage Azure identities             ~20–25%
├── Implement and manage storage        ~15–20%
├── Deploy and manage Azure compute     ~20–25%
├── Implement and manage virtual nets   ~15–20%
└── Monitor and maintain resources      ~10–15%

MOST USED COMMANDS
├── az group create / delete
├── az vm create / deallocate / resize
├── az network vnet create / peer
├── az storage account create
├── az backup job list
└── Get-AzVM / New-AzVm / Stop-AzVM

CLEANUP PATTERN (every lab)
├── Portal:      Resource Group → Delete
├── PowerShell:  Remove-AzResourceGroup -Name <rg>
└── CLI:         az group delete --name <rg>
```

---

<div align="center">

**AZ-104 · Microsoft Azure Administrator · Official Curriculum**

*This guide is maintained as a training reference for AZ-104 exam preparation.*  
*All lab content © Microsoft Learning. Lab exercises available at [github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator](https://github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator)*

[![Made with ❤️ for Azure Learners](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20for-Azure%20Learners-0078D4?style=flat-square)](https://learn.microsoft.com/en-us/certifications/azure-administrator/)

</div>
