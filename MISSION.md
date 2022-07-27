# Project Mission

Our goal is to create a bounty management platform. Everyone can log in to the application via wallet. The platform has two primary roles - `bounty creator` and `bounty worker`. One wallet can be creator and worker simultaneously - there is no restriction. The bounty creator can create a project and bounties under it. Each bounty must contain a revenue entirely paid by the creator during the creation process. The bounty workers can assign a bounty to themselves and get paid after the bounty is resolved.

## Key Features

There are many similar platforms on the internet - centralized and decentralized. In the following chapter, we describe our key features. The key features solve a specific problem the labor market faces, described in the [Project Vision](./VISION.md) document.

### Blockchain

The platform uses blockchain as an authority. There is no central authority that makes decisions or holds the bounty revenues. The platform is open to all people around the world and fully anonymous. The bounty revenues are also stored on the blockchain, meaning no third-party centralized "service" holds these revenues. One of our core values is transparency which is also solved by blockchain technology. We decided to use Solana as blockchain technology.

### Revenue System

The application must be trustworthy for all participants, especially for bounty workers. If you spend your time on a bounty, you must be sure that you will be paid for the job. Withdrawing the revenue is possible after the bounty state is set to specific states. The platform supports `SOL` and `USDC` tokens as revenues. We plan to support more tokens in the future, but each will be thoroughly selected. This decision is related to the trustworthiness of the platform.

### Automation

Our goal is to introduce a robust state machine mechanism and automation for bounties. For example, it will be easy to use the app for both parties, especially switching between states. There will be a mechanism recommending the optimal price for each bounty, a description and specification mechanism, and educational materials about pricing and salaries.

### Same Rules For Both Parties

The bounty creator and worker are equal to each other. They need each other - they are partners. It means there will be the same rules for both parties - at the application and bounty levels.
