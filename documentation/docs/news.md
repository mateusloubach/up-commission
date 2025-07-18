# Deployment Versions

## Current Production Version
_Current build:_ `BUILD_SHA_HERE`
**v2.3.1** - Deployed on July 15, 2025 at 14:30 UTC

---

## Version History

### [v2.3.1] (July 17, 2025)
- **Status**: Production
- **Deployed by**: [mateusloubach]
- **Deployment time**: 14:30 UTC
- **Build**: #1247
- **Git commit**: `BUILD_SHA_HERE`
- **Features**:
  - Fixed commission calculation bug for tier 3 agents
  - Updated payment processing flow
  - Enhanced security for API endpoints
- **Database migrations**: None
- **Rollback plan**: Available (v2.3.0)

### [v2.3.1] (July 15, 2025)
- **Status**: Production
- **Deployed by**: john.doe@agency.com
- **Deployment time**: 14:30 UTC
- **Build**: #1247
- **Git commit**: `a7f8c9d2`
- **Features**:
  - Fixed commission calculation bug for tier 3 agents
  - Updated payment processing flow
  - Enhanced security for API endpoints
- **Database migrations**: None
- **Rollback plan**: Available (v2.3.0)

### v2.3.0 (July 10, 2025)
- **Status**: Superseded
- **Deployed by**: jane.smith@agency.com
- **Deployment time**: 09:15 UTC
- **Build**: #1239
- **Git commit**: `b3e4f5a1`
- **Features**:
  - New commission tier system
  - Agent dashboard improvements
  - Performance optimizations
- **Database migrations**: 3 migrations applied
- **Rollback plan**: Completed successfully

### v2.2.5 (July 5, 2025)
- **Status**: Superseded
- **Deployed by**: mike.johnson@agency.com
- **Deployment time**: 16:45 UTC
- **Build**: #1228
- **Git commit**: `c9d1e2f3`
- **Features**:
  - Hotfix for payment gateway timeout
  - Updated SSL certificates
- **Database migrations**: None
- **Rollback plan**: Not needed

### v2.2.4 (June 28, 2025)
- **Status**: Superseded
- **Deployed by**: sarah.wilson@agency.com
- **Deployment time**: 11:20 UTC
- **Build**: #1215
- **Git commit**: `d4e5f6a7`
- **Features**:
  - Monthly commission report generation
  - Email notification system
  - UI/UX improvements
- **Database migrations**: 2 migrations applied
- **Rollback plan**: Available

---

## Deployment Environments

### Production
- **URL**: https://commission.agency.com
- **Current version**: v2.3.1
- **Last updated**: July 15, 2025

### Staging
- **URL**: https://staging-commission.agency.com
- **Current version**: v2.4.0-beta.1
- **Last updated**: July 16, 2025

### Development
- **URL**: https://dev-commission.agency.com
- **Current version**: v2.4.0-dev
- **Last updated**: July 17, 2025

---

## Quick Links
- [Release Notes](./release-notes.md)
- [mateusloubach](https://github.com/mateusloubach/)
- [Deployment Guide](./deployment-guide.md)
- [Rollback Procedures](./rollback-procedures.md)
- [Build Pipeline](https://build.agency.com/up-commission)
  [v2.3.1]: https://mateusloubach.github.io/up-commission/277edf2/