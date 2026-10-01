# Multi-Line-Insurance-Policy-and-Claims-Management-System
# Multi-Line Insurance Policy and Claims Management System

## Project Overview

A Salesforce-based insurance management solution supporting Vehicle,
Property, and Life insurance policies and claims.

## Objectives

- Standardize policy quoting and issuance
- Automate claim routing
- Provide a 360-degree customer, policy and claim view
- Automate high-value claim approval
- Provide adjusters with a claims dashboard

## Insurance Lines

- Vehicle Insurance
- Property Insurance
- Life Insurance

## Salesforce Technologies

- Custom Objects
- Record Types
- Field Sets
- Validation Rules
- Screen Flows
- Record-Triggered Flows
- Apex
- Lightning Web Components
- Approval Processes
- Permission Sets
- Sharing Rules

## Project Milestones

### Milestone 1
Core Data Model & Policy Configuration

### Milestone 2
Complex Policy Issuance & Claim Routing

### Milestone 3
Claims Adjuster LWC Dashboard

### Milestone 4
Advanced Claim Processing, Security & Code Setup

## Key Components

### Apex
- PremiumCalculator
- ClaimsAdjusterController
- ClaimsAdjusterControllerTest

### Lightning Web Components
- claimsDashboardLwc
- claimTileLwc

### Flows
- AutoQuotingFlow
- ClaimRoutingFlow
- SubmissionAutomationFlow
- ClaimApproverScreenFlow
- ClaimPolicyHolderStateUpdate

## Security

The system uses Permission Sets and Sharing Rules
to separate Agent, Adjuster and Manager responsibilities.

## Testing

Apex test classes and functional test cases are included
under the Testing directory.

## Deployment

Refer to Deployment/Deployment-Guide.md.
