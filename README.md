Deployment of a self-hosted music tracking stack (Maloja and MultiScrobbler) designed to replace proprietary services like Last.fm.

    MultiScrobbler: Acts as the backend engine, gathering playcount data from multiple sources (Spotify, Plex, etc.).

    Maloja: Serves as the self-hosted frontend for displaying rich music listening history and personal statistics.

Technical Highlights:

    Refactored Environment Logic: Migrated the original configuration to support Docker secrets and environment variables for enhanced security.

    Persistence Strategy: Implemented bind-mount persistence to ensure stats and database integrity across container updates.

    Infrastructure as Code: Orchestrated via Docker Compose for a stable, "set-and-forget" deployment.
