# Test Data for Album Creation, Release, Storage, and Delivery Workflow

## Table of Contents
1. [Capture Application Test Data](#capture-application-test-data)
2. [Release Application Test Data](#release-application-test-data)
3. [Storage Application Test Data](#storage-application-test-data)
4. [Delivery Application Test Data](#delivery-application-test-data)

---

## 1. Capture Application Test Data

### 1.1 Artist Management Test Data

| Artist Name   | Biography                           | Profile Image URL        | Contract Start Date | Contract End Date | Royalties (%) |
|---------------|-------------------------------------|--------------------------|---------------------|-------------------|---------------|
| John Doe      | A talented rock singer and songwriter. | [link_to_image.jpg](#)   | 01-Jan-2020         | 01-Jan-2025       | 12%           |
| Jane Smith    | An upcoming indie pop artist.        | [link_to_image.jpg](#)   | 01-Jun-2021         | 01-Jun-2026       | 15%           |

### 1.2 Album Creation Test Data

| Album Title            | Artist(s)       | Release Year | Genre       | Tracklist                                 | Artwork URL            |
|------------------------|-----------------|--------------|-------------|-------------------------------------------|------------------------|
| "Echoes of Tomorrow"    | John Doe        | 2024         | Rock        | Track 1: "Tomorrow", Track 2: "Echoes"    | [album_artwork.jpg](#) |
| "Whispers in the Night" | Jane Smith      | 2024         | Indie Pop   | Track 1: "Whisper", Track 2: "Nightfall"  | [album_artwork.jpg](#) |

### 1.3 Sound Labeling Test Data

| Track Title            | Genre       | Mood      | Tempo    |
|------------------------|-------------|-----------|----------|
| "Tomorrow"             | Rock        | Energetic | Fast     |
| "Whisper"              | Indie Pop   | Calm      | Medium   |

---

## 2. Release Application Test Data

### 2.1 Release Planning Test Data

| Album Title            | Release Date | Pre-release Date | Marketing Plan        |
|------------------------|--------------|-------------------|-----------------------|
| "Echoes of Tomorrow"    | 15-Feb-2024  | 01-Feb-2024      | Social Media Campaign |
| "Whispers in the Night" | 10-Mar-2024  | 01-Mar-2024      | Music Video Launch    |

### 2.2 Pre-Release Activities Test Data

| Album Title            | Promotional Material URL  | Campaign Type    |
|------------------------|---------------------------|------------------|
| "Echoes of Tomorrow"    | [promo_image.jpg](#)       | Social Media    |
| "Whispers in the Night" | [music_video.mp4](#)       | Video Promotion |

### 2.3 Release Coordination Test Data

| Album Title            | Distribution Channels     | Release Status |
|------------------------|---------------------------|----------------|
| "Echoes of Tomorrow"    | Spotify, Apple Music, CD  | Released       |
| "Whispers in the Night" | Spotify, Amazon Music      | Scheduled      |

---

## 3. Storage Application Test Data

### 3.1 Centralized Storage Test Data

| Album Title            | Audio File URL               | Artwork File URL               | Metadata File URL               |
|------------------------|-----------------------------|--------------------------------|---------------------------------|
| "Echoes of Tomorrow"    | [audio_file.mp3](#)         | [album_artwork.jpg](#)         | [metadata.json](#)             |
| "Whispers in the Night" | [audio_file.mp3](#)         | [album_artwork.jpg](#)         | [metadata.json](#)             |

### 3.2 Metadata Management Test Data

| Album Title            | Metadata Field        | Value                        |
|------------------------|-----------------------|------------------------------|
| "Echoes of Tomorrow"    | Genre                 | Rock                         |
| "Whispers in the Night" | Artist Name           | Jane Smith                   |

### 3.3 Digital Rights Management (DRM) Test Data

| Album Title            | DRM Status  |
|------------------------|-------------|
| "Echoes of Tomorrow"    | Enabled     |
| "Whispers in the Night" | Disabled    |

---

## 4. Delivery Application Test Data

### 4.1 Distribution Management Test Data

| Album Title            | Distribution Channels     | Distribution Status |
|------------------------|---------------------------|---------------------|
| "Echoes of Tomorrow"    | Spotify, Apple Music, CD  | Distributed         |
| "Whispers in the Night" | Spotify, Amazon Music      | Pending             |

### 4.2 Logistics and Tracking Test Data

| Album Title            | Tracking Number     | Delivery Status  | Expected Delivery Date |
|------------------------|---------------------|------------------|------------------------|
| "Echoes of Tomorrow"    | 12345XYZ           | In Transit       | 10-Feb-2024            |
| "Whispers in the Night" | 67890ABC           | Delivered        | 05-Mar-2024            |

### 4.3 Compliance and Documentation Test Data

| Album Title            | Compliance Document URL     | Document Status  |
|------------------------|-----------------------------|------------------|
| "Echoes of Tomorrow"    | [compliance.pdf](#)         | Approved         |
| "Whispers in the Night" | [compliance.pdf](#)         | Pending          |

---

## General Notes

- **Test Data Integrity**: Ensure all the test data provided is valid and properly linked.
- **Data Cleanup**: After completing the tests, ensure that the data is cleaned up to prevent conflicts during future tests.
- **Role-based Access**: Test users with different roles (Admin, User) to ensure data access is properly restricted.

---

This test data will help you in performing the necessary testing for the **Capture**, **Release**, **Storage**, and **Delivery** applications. Use this data as a reference during manual or automated tests to validate system functionality.
