# Community Component Showcase

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F{YOUR_GITHUB_USERNAME}%2Fcommunity-component-showcase)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

An open-source application for browsing, sharing, and discovering community-built UI components generated with AI. This project serves as a template for building full-stack applications on Vercel with a modern architecture.

<!-- Add a screenshot of the live application here -->
![App Screenshot ](https://lh3.googleusercontent.com/fife/ALs6j_EkvGKX9CSmZEMj3c2kIAN5x_NUmn6mp3EpWizxUA4VhvH646VTsmSQEoDQ5UZvyGcexzCpFB9oXiWXbN02duo7mLHZ52kSWOOLOjY9W4vqa1Te1mJfJPNsrM9Apr88Me2hOjY2Ifxp7JKiJy5Ytcvy3FoEGwWl21m8SsQibzOEJeJPMcbqVr4FLgNqITcfshVpqyOdlOqZuL2VXdpd0Ot8eMct_5C9Y8CoJzFInebz9PhsonVhz-c3Hkb4pm_wgRcdzVJzhpnX5jmHrzr1dkB4YJuhKO8p1p_V5Sr7EAkVGrCbAWR5eqrkUc2EIkk_ao2p6OQnN3qonaeMON-hpdtt2EZHarOzk5oATmlOLqMdCctSNconxK2cfdtDdVUCaL8KidOXCPQ4UXohLXXSsl1GdkfCS8YovA8NBL_JLg2saUORasYKEvk_8SsZzWAij-LjUgQdyIB350_5vbc_UWSk4qiSgdcRNJyXHLJfqGJG3TFuFpBfFWxL-t0kl-IZnnftDI4yP-Y59SWCsdCG26pLs_ReZfUP2KsoT7qMA9-n8PFziEQB1eFlY5s8rRVDEpVmCWg63nbsuHAWgU_cCPZFnBIoPRjnnXA0tHUG6r8xmuFHjdje009th1hWruVZK0ofnYRzvXkijBnr3Pc_U5wDUoSwOPWHDoc-9cmZytlFRDGe6pNFLeXrOSHVJjUzrKFx9LHdu9yvQ4Loa4gzgXpHTb27tmiLcnxZmUuevJsS4AglzJYHBfUFwM6xVehCuHNDyh5bAhbJszmxQ1IFpFo4khQBXwAXacgrIwfSUqKdJ-76PGvc6XsA0FzhuRY9vV1O8YGDsZt--opLSL-YVf4DlWTZPbx4CFTAsqWn2-nOtLIvP-heKzGT19vIbf91xiYXn3L0xnryKu9too95SaWfz_FAS0OpjzYEWKLJc_4XEMwY-6RycQfuSWLRqWacqpHFOWb9HlneLWfwz-9L7W2aQYop4Ctcuyr9acM2FL2hR8KGyBHnOCfFeZptA3CloeaUZun7YEavpnqoh-RTqFTFTSuFdlHA94v7NU299Z9CXiFZdmj3e56KUZwJLutErHe2izXuxKIDtWgLZFTtrjiy-CTNm0tmw1q79cH981QEAWYXSUoIkYb1mBp4JLuWaTzDgXta7Cp3O9OO3U4XOiCo-QjqtjN6LtwAIQR8trcJxYhdYvLKnGXkzOTsNTq-lduPEpf3ZO-NY3BEEN3H7rh72h55cQySPMa37z21MdKrV5-lGbZOLqC14983O-3W85Le-wLeF_EhBZ1AgcTPi79wnVMaM2lF6z7wfJ8CiN7A7qbu5n-228Xt56clag3DPcik2wbl-l4_aquhi9Gsz5O5WplgFB7Ova4LwPu0PXZ3JKQOKEE=s1024)

## Overview

The Community Component Showcase is a dynamic gallery where developers can explore UI components created by the community. Users can search and filter through submissions, copy the generation prompts to use them in their own projects, and (with authentication) submit their own creations.

This project is not just a useful tool but also a learning resource and a starter kit for building applications with the Vercel stack.

## Features

-   **Modern Dark UI:** A sleek, responsive interface built with Tailwind CSS.
-   **Dynamic Filtering & Search:** Easily find components by category or keywords.
-   **User Authentication:** Secure sign-up and login functionality powered by Clerk.
-   **Community Submissions:** Authenticated users can contribute their own components.
-   **Full-Stack Architecture:** Built on Next.js with serverless API routes.
-   **Scalable Database:** Uses Supabase (or any Postgres provider like Neon) for data storage.
-   **One-Click Deployment:** Ready to be deployed on Vercel.

## Tech Stack

-   **Framework:** [Next.js](https://nextjs.org/)
-   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
-   **Authentication:** [Clerk](https://clerk.com/)
-   **Database:** [Supabase](https://supabase.io/) (or [Neon](https://neon.tech/))
-   **Deployment:** [Vercel](https://vercel.com/)

## Getting Started

Follow these instructions to get a local copy up and running for development and testing purposes.

### Prerequisites

-   Node.js (v18 or later)
-   npm, yarn, or pnpm
-   A Vercel account (for deployment)
-   A Clerk account
-   A Supabase project

### Installation

1.  **Fork and Clone the Repository**
    ```sh
    git clone [https://github.com/](https://github.com/){YOUR_GITHUB_USERNAME}/community-component-showcase.git
    cd community-component-showcase
    ```

2.  **Install Dependencies**
    ```sh
    npm install
    ```

3.  **Set Up Environment Variables**
    Create a `.env.local` file in the root of your project and add the following environment variables. You can get these keys from your Clerk and Supabase project dashboards.

    ```env
    # Clerk Keys
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    # Supabase Keys
    NEXT_PUBLIC_SUPABASE_URL=
    NEXT_PUBLIC_SUPABASE_ANON_KEY=
    ```

4.  **Run the Development Server**
    ```sh
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## How to Contribute

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
