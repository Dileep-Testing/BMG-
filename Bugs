# Bug List for Album Creation, Release, Storage, and Delivery Workflow

## Table of Contents
1. [Capture Application](#capture-application)
   - 1.1. Artist Management
   - 1.2. Album Creation
   - 1.3. Sound Labeling
2. [Release Application](#release-application)
   - 2.1. Release Planning
   - 2.2. Pre-Release Activities
   - 2.3. Release Coordination
3. [Storage Application](#storage-application)
   - 3.1. Centralized Storage
   - 3.2. Metadata Management
   - 3.3. Digital Rights Management (DRM)
4. [Delivery Application](#delivery-application)
   - 4.1. Distribution Management
   - 4.2. Logistics and Tracking
   - 4.3. Compliance and Documentation

---

## 1. Capture Application

### 1.1 Artist Management

- **Bug 1.1.1**: Unable to save artist profile after entering all required information.
  - **Description**: Clicking the **Save** button doesn't store the artist's information.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Artist Management**.
    2. Enter artist's name, biography, and upload an image.
    3. Click **Save**.
  - **Expected Result**: The artist profile should be saved successfully.
  - **Actual Result**: The artist profile is not saved.

- **Bug 1.1.2**: Artist profile image upload fails with valid image formats.
  - **Description**: Images in supported formats (.jpg, .png) fail to upload.
  - **Severity**: Medium
  - **Steps to Reproduce**:
    1. Navigate to **Artist Management**.
    2. Upload an image (e.g., .jpg or .png).
    3. Click **Save**.
  - **Expected Result**: The image should upload successfully.
  - **Actual Result**: The image fails to upload.

---

### 1.2 Album Creation

- **Bug 1.2.1**: Album creation fails when selecting the artist.
  - **Description**: Selecting an artist to associate with an album results in an error.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Album Creation**.
    2. Select an artist.
    3. Enter album details (title, genre, etc.).
    4. Click **Save**.
  - **Expected Result**: The album should be created with the selected artist.
  - **Actual Result**: The album is not created, and an error is displayed.

- **Bug 1.2.2**: Unable to upload album artwork.
  - **Description**: Uploading artwork (.jpg, .png) results in an error or crash.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Album Creation**.
    2. Click **Upload Artwork** and select a file.
    3. Click **Save**.
  - **Expected Result**: The album artwork should be uploaded and saved successfully.
  - **Actual Result**: The upload fails with no clear error message.

---

### 1.3 Sound Labeling

- **Bug 1.3.1**: Metadata labels are not saved after editing.
  - **Description**: After editing track metadata (e.g., genre, mood), the changes are not saved.
  - **Severity**: Medium
  - **Steps to Reproduce**:
    1. Navigate to **Sound Labeling**.
    2. Select a track and edit metadata.
    3. Click **Save**.
  - **Expected Result**: Metadata changes should be saved successfully.
  - **Actual Result**: The changes are not saved.

- **Bug 1.3.2**: Inconsistent metadata display after saving.
  - **Description**: After saving metadata for a track, the labels are not consistently displayed in the correct fields.
  - **Severity**: Low
  - **Steps to Reproduce**:
    1. Edit metadata for a track.
    2. Save the changes.
  - **Expected Result**: All metadata labels should display correctly.
  - **Actual Result**: Some labels are missing or displayed incorrectly.

---

## 2. Release Application

### 2.1 Release Planning

- **Bug 2.1.1**: Release date cannot be set.
  - **Description**: When trying to set a release date, the input field is unresponsive or does not allow date selection.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Release Planning**.
    2. Try to set a release date.
  - **Expected Result**: The release date should be set successfully.
  - **Actual Result**: The input field is unresponsive.

- **Bug 2.1.2**: Release date is not saved correctly.
  - **Description**: After setting a release date, it is not saved and remains empty.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Release Planning**.
    2. Set the release date.
    3. Save and navigate away.
  - **Expected Result**: The release date should be saved.
  - **Actual Result**: The release date is not saved.

---

### 2.2 Pre-Release Activities

- **Bug 2.2.1**: Promotional materials not displaying correctly.
  - **Description**: Uploaded promotional materials (e.g., images, videos) are not displayed correctly in the preview section.
  - **Severity**: Medium
  - **Steps to Reproduce**:
    1. Navigate to **Pre-Release Activities**.
    2. Upload promotional materials.
    3. Check the display of materials.
  - **Expected Result**: Materials should display correctly.
  - **Actual Result**: Materials are not displayed or shown in a distorted manner.

- **Bug 2.2.2**: Incorrect metadata for promotional materials.
  - **Description**: Metadata (e.g., description, keywords) for promotional materials is not saved correctly.
  - **Severity**: Low
  - **Steps to Reproduce**:
    1. Upload promotional material with metadata.
    2. Save and check the material.
  - **Expected Result**: Metadata should be saved correctly.
  - **Actual Result**: Metadata is not saved, or incorrect data is shown.

---

### 2.3 Release Coordination

- **Bug 2.3.1**: Release coordination fails to trigger distribution.
  - **Description**: When attempting to release the album across platforms, the distribution does not start or fails midway.
  - **Severity**: Critical
  - **Steps to Reproduce**:
    1. Navigate to **Release Coordination**.
    2. Select distribution channels.
    3. Confirm release.
  - **Expected Result**: The album should be released across all selected platforms.
  - **Actual Result**: Distribution fails, and the album is not released.

---

## 3. Storage Application

### 3.1 Centralized Storage

- **Bug 3.1.1**: Uploading files to storage results in a timeout.
  - **Description**: Large album assets cause the upload process to timeout or fail.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Centralized Storage**.
    2. Upload a large file (e.g., high-resolution artwork or audio file).
  - **Expected Result**: The file should be uploaded successfully.
  - **Actual Result**: The upload fails due to a timeout error.

- **Bug 3.1.2**: Inability to access stored assets.
  - **Description**: Once assets are uploaded, some users are unable to access them due to permission issues.
  - **Severity**: Medium
  - **Steps to Reproduce**:
    1. Navigate to **Centralized Storage**.
    2. Try to access an uploaded asset.
  - **Expected Result**: The asset should be accessible.
  - **Actual Result**: Users encounter access errors or denied permissions.

---

### 3.2 Metadata Management

- **Bug 3.2.1**: Metadata not syncing across platforms.
  - **Description**: Metadata updates made on the backend do not sync with distribution platforms.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Edit metadata in the system.
    2. Release album across platforms.
  - **Expected Result**: Metadata should be correctly displayed on all platforms.
  - **Actual Result**: Metadata is incorrect or missing on some platforms.

- **Bug 3.2.2**: Metadata is being overwritten during updates.
  - **Description**: When metadata is updated, some fields are overwritten, losing important data.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Update metadata for an album.
    2. Save and verify fields.
  - **Expected Result**: Metadata should update correctly without overwriting necessary fields.
  - **Actual Result**: Some fields are overwritten.

---

### 3.3 Digital Rights Management (DRM)

- **Bug 3.3.1**: DRM protection does not apply to certain audio files.
  - **Description**: Some audio files bypass DRM protection, allowing unauthorized access.
  - **Severity**: Critical
  - **Steps to Reproduce**:
    1. Apply DRM to an album.
    2. Attempt to play or share the files.
  - **Expected Result**: DRM protection should be applied to all files.
  - **Actual Result**: Some files are unprotected.

---

## 4. Delivery Application

### 4.1 Distribution Management

- **Bug 4.1.1**: Distribution channels not updating correctly.
  - **Description**: After selecting distribution channels, changes are not saved or updated.
  - **Severity**: Medium
  - **Steps to Reproduce**:
    1. Navigate to **Distribution Management**.
    2. Select channels for album distribution.
    3. Save and verify the selection.
  - **Expected Result**: The distribution channels should be updated.
  - **Actual Result**: Distribution channels are not saved correctly.

---

### 4.2 Logistics and Tracking

- **Bug 4.2.1**: Tracking number lookup fails for valid shipments.
  - **Description**: Entering a valid tracking number returns an error or no data.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Logistics and Tracking**.
    2. Enter a valid tracking number.
  - **Expected Result**: Delivery status and tracking info should display.
  - **Actual Result**: An error message or no tracking data is returned.

---

### 4.3 Compliance and Documentation

- **Bug 4.3.1**: Compliance documentation cannot be uploaded.
  - **Description**: The system fails to upload compliance documents necessary for album release.
  - **Severity**: High
  - **Steps to Reproduce**:
    1. Navigate to **Compliance and Documentation**.
    2. Attempt to upload a compliance document.
  - **Expected Result**: The document should be uploaded and saved.
  - **Actual Result**: The upload fails, and no document is saved.

---

This list includes some of the most common bugs you may encounter across the applications. Paste this into your **README.md** to keep track of known issues in your repo.
