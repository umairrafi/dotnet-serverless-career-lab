        # .NET Serverless Career Lab

        Project-based interview prep aligned to [career-lab-master-plan](https://github.com/umairrafi/muhammad-umair-portfolio/blob/main/docs/career-lab-master-plan.md) and [complete catalog](https://github.com/umairrafi/muhammad-umair-portfolio/blob/main/docs/career-lab-complete-catalog.md).

        ## Who this is for

        - Backend engineers building public proof for job switch (UAE/GCC — 25k AED framing in master plan §6)
        - Developers mapping **engineering-profile** evidence to buildable labs (no employer secrets)

        ## Prerequisites

        [payments-career-lab](https://github.com/umairrafi/payments-career-lab) optional · AWS basics

        ## Capstone: FriendOffer Platform

        Evolving codebase in [`capstone/friend-offer-platform/`](capstone/friend-offer-platform/) — run instructions in capstone README.

        ## Roadmap

        | Week | Topic | Folder | Objective |
        |------|-------|--------|-------------|
        | **1** | Lambda anatomy & DI | [week-01-lambda-di](weeks/week-01-lambda-di/) | One Lambda per endpoint, DI container |
| **2** | Validation & legacy JSON | [week-02-validation-dtos](weeks/week-02-validation-dtos/) | DataAnnotations, backward-compatible DTOs |
| **3** | JWT + web token | [week-03-jwt-web-token](weeks/week-03-jwt-web-token/) | DB-backed guid check |
| **4** | Native AOT publish | [week-04-native-aot](weeks/week-04-native-aot/) | Trim constraints, no reflection |
| **5** | Shared library design | [week-05-shared-library](weeks/week-05-shared-library/) | Common auth/config |
| **6** | MySQL + RDS Proxy concept | [week-06-mysql-rds-proxy](weeks/week-06-mysql-rds-proxy/) | Local MySQL lab; IAM auth narrative |
| **7** | Integration tests | [week-07-integration-tests](weeks/week-07-integration-tests/) | xUnit handler tests |
| **8** | FCM HTTP v1 | [week-08-fcm-http-v1](weeks/week-08-fcm-http-v1/) | JWT signing without heavy SDK |
| **9** | API Gateway OpenAPI | [week-09-api-gateway-openapi](weeks/week-09-api-gateway-openapi/) | aws_proxy import |
| **10** | Capstone ship | [week-10-capstone-ship](weeks/week-10-capstone-ship/) | Four Lambdas + push stub + OpenAPI snippet |

        ## Weekly structure

        ```
        week-NN-slug/
        ├── README.md
        ├── 01-lessons/
        ├── 02-hands-on/
        ├── 03-exercises/
        └── 04-capstone-project/
        ```

        ## Start here

        ```bash
        cd weeks/week-01-lambda-di
        cat README.md
        ```

        ---

        Built by [Muhammad Umair Virk](https://muhammad-umair.pages.dev) · Backend · UAE
