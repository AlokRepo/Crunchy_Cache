# CrunchyScroll Cache Repository

This repository acts as a decentralized database cache for the CrunchyScroll application. It stores pre-resolved mapping information, TVDB episode metadata (including episode names, absolute numbers, and images), and resolved server stream URLs.

## Directory Structure

*   **`mappings/tvdb-to-anilist/`**: Maps TVDB series ID + season number to AniList/MAL IDs.
*   **`metadata/tvdb/`**: Pre-fetched TVDB episode list metadata (including episode images, descriptions, titles).
*   **`streams/`**: Maps AniList ID + episode number to resolved stream URLs (MegaPlay, Nest, Cage) for both subbed and dubbed options.

## Setup

1. Create a public or private repository with this name on GitHub.
2. In the CrunchyScroll app, go to the **Account Settings** page.
3. Tap the **Version Text** at the very bottom **7 times** to unlock Developer Mode.
4. Input your GitHub Personal Access Token (PAT) with `repo` scope.
5. Set your repository path (e.g. `yourusername/crunchyscroll-cache`).
