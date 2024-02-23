# hubs-directory
A directory of Mozilla Hubs instances

## How to add a directory
Creating a public directory of Mozilla Hubs rooms on GitHub involves a few straightforward steps. This guide is designed for a non-technical audience to easily follow along.

### **Step 1: Understanding GitHub**

GitHub is a web-based platform used for version control and collaboration. It allows users to contribute to projects via Forking and Pull Requests (PRs).

### **Step 2: Creating a GitHub Account**

- Go to [github.com](https://github.com) and sign up for a free account.

### **Step 3: Finding the Repository**

- Navigate to the repository containing the Mozilla Hubs room directory.

### **Step 4: Opening an Issue (Optional)**

Discuss new additions freely before making changes:
1. Click "Issues" > "New Issue".
2. Describe the Mozilla Hubs room you wish to add.

### **Step 5: Creating a Pull Request**

1. Fork the repository.
2. Navigate to the README.md and click the pencil icon to edit.
3. Add your room in the markdown format provided below:
    ```markdown
    | Title                  | Screenshot | Description |
    |------------------------|------------|-------------|
    | [Your Room Title Here](https://example.com) | ![Alt text](/thumbnails/yourimage.jpg) | Your Description Here |
    ```
4. Add the screenshot thumbnail (see below for instructions)
5. Propose the change with a meaningful commit message.
6. Click "Create Pull Request".

### **Step 6: PR Review and Approval**

Wait for the project maintainers to review and merge your PR.

### **Adding a Thumbnail Screenshot**

When you contribute a room to the directory, including a thumbnail screenshot makes it visually appealing and provides a quick preview of the room. Here are the guidelines for adding screenshots:

#### **Naming Convention**

- Name your screenshot file using the following format: `[RoomName]-thumbnail.[ext]`, where `[RoomName]` is a concise version of your room title and `[ext]` is the file extension based on the image format (e.g., 'community-meetup-thumbnail.png').
- Use dashes (-) instead of spaces, and keep the name lowercase to ensure consistency and compatibility.

#### **Image Specifications**

- **Preferred Dimensions**: Aim for an image size of `1280x720 pixels` (720p). This dimension works well across devices, offering a balance between clarity and file size.
- **Supported Formats**: GitHub supports a range of image formats. For thumbnails, you should use either `JPEG` (.jpg/.jpeg) for photos or complex images, or `PNG` (.png) for images with transparency or simpler graphics.
- **Maximum File Size**: Keep the image file size under `1MB` to ensure quick loading times and to be considerate of those with bandwidth limitations.

#### **Uploading Screenshots**

1. Upload the image to the `thumbnails` folder within the repository. You can do this by navigating to the folder, clicking "Add file" > "Upload files", and then selecting your pre-named image file.
2. Reference the image in the README.md by including it in your room's entry using markdown image syntax: `![Alt text](/thumbnails/[YourImageFileName].[ext])`, replacing `[YourImageFileName].[ext]` with the name of your uploaded file.

### **Privacy Implications**

Ensure you are comfortable sharing the room's details publicly. All submitted information will be accessible on GitHub.

Contributing to open-source projects like this directory not only benefits the wider community but can also be enriching for the contributors.

By following these guidelines, you help maintain a consistent and professional appearance for the Mozilla Hubs rooms directory.




## Directory

| Title                  | Screenshot | Description |
|------------------------|------------|-------------|
| [Community Meetup]([https://example.com](https://hubs.mozilla.com/NXdJLZB/community-meetup/)) | ![Alt text](/thumbnails/community-meetup.jpg) | Mozilla Hub's official weekly community meetup. Meets most Fridays at 1400 EST. Check out the [Mozilla Hubs official Discord server  | https://discord.com/invite/hubs-498741086295031808] for additional info. |
| [Your Room Title Here](https://example.com) | ![Alt text](/thumbnails/yourimage.jpg) | Your Description Here | <!-- Leave this line in place; place new rooms above this line -->

