<div align="center">

```text
  _        _ _____ ______     _____ _     ____  _  _ ____  
 | |      / | ____|_   _|   / ____| |   / __ \| || |  _ \ 
 | |     / /|  _|   | |    | |    | |  | |  | | || | |_) |
 | |___ / / | |___  | |    | |____| |__| |__| |__   _|  _ < 
 |______/_/  |_____| |_|     \_____|_____\____/   |_||_| \_\
                                                            
===================================================================
|             BALINT LOJT | JUNIOR CLOUD ENGINEER                 |
|       AWS • Azure • GCP • Terraform • GitHub Actions • FinOps   |
===================================================================

lojt-cloud@github.com:~$ cat profile.json
{
  "location": "Amsterdam, Netherlands",
  "education": "Ironhack Cloud Engineering Bootcamp (Top of Class)",
  "experience": "1.5 Years IT Systems Administration & Support",
  "certifications": {
    "active": ["Azure Fundamentals (AZ-900)"],
    "in_progress": [
      "HashiCorp Certified: Terraform Associate (004)",
      "AWS Certified: Solutions Architect Associate (SAA-C03)"
    ]
  },
  "background": "Ex-International Ski & Snowboard Instructor (3 Continents)"
}

lojt-cloud@github.com:~$ ./deploy_capstone.sh --project "BOUNCER"
> Provisioning Multi-AZ AWS Infrastructure via Terraform... [OK]
> Authenticating GitHub Actions CI/CD via OIDC & Checkov... [OK]
> Applying FinOps policy: Ephemeral environment auto-teardown... [ACTIVE]

lojt-cloud@github.com:~$ exit
