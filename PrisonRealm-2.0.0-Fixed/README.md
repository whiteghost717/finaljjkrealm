# PrisonRealm 2.0.0 — fixed source package

This source package contains the complete `PrisonRealmPlugin.java`, `plugin.yml`, `config.yml`, Gradle files, and GitHub Actions workflow.

## Build with GitHub Actions
1. Upload the **contents** of this folder to the root of your GitHub repository. `.github`, `build.gradle`, `settings.gradle`, and `src` should be directly at repository root.
2. Commit the files.
3. Open **Actions** and wait for **Build PrisonRealm** to finish.
4. Download the `PrisonRealm-JAR` artifact from a successful run.

The workflow uses Java 25 and Gradle. This source has not been verified by a successful Gradle build in this environment; confirm that GitHub Actions succeeds before installing the JAR on your server.

## Commands
- `/prisonrealm give <player>` — give a Prison Realm item (admin permission).
- `/prisonrealm setprison` — set the prison destination at your current location.
- `/prisonrealm status` — show status.
- `/prisonrealm sealed` — list sealed players.
- `/prisonrealm release <player>` — admin emergency release.
- `/seal <player>` — seal a target after your ritual.
- Place a Prison Realm block as the release station, then `/unseal <player>` — original captor only.

A resource pack is needed for a custom cube appearance; CustomModelData alone does not provide the model.
