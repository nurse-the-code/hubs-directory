# hubs-directory
A public directory of Mozilla Hubs instances

## Table of Contents
- [Directory](#directory)
- [How to add a room](#how-to-add-a-room)


## Directory

| Title                  | Screenshot | Description |
|------------------------|------------|-------------|
| [Community Meetup](https://hubs.mozilla.com/NXdJLZB/community-meetup/)) | ![Alt text](/thumbnails/community-meetup-thumbnail.jpg) | Mozilla Hub's official weekly community meetup. Meets most Fridays at 1400 EST. Check out the Mozilla Hubs official Discord server for additional info. |
| [Your Room Title Here](https://example.com) | ![Alt text](/thumbnails/your-image-thumbnail.jpg) | Your Description Here | <!-- Leave this line in place; place new rooms above this line -->


## How to add a room
Adding a room to the a public directory of Hubs rooms on GitHub involves a few straightforward steps. This guide is designed for a non-technical audience to easily follow along.

### **Step 1: Understanding GitHub**

GitHub is a web-based platform used for version control and collaboration. It allows users to contribute to projects via Forking and Pull Requests (PRs).

### **Step 2: Creating a GitHub Account**

- Go to [github.com](https://github.com) and sign up for a free account.

### **Step 3: Finding the Repository**

- Navigate to the [repository | https://github.com/nurse-the-code/hubs-directory/] containing the Hubs room directory.

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
4. Add the screenshot thumbnail ([see below](#adding-a-thumbnail-screenshot) for instructions).
5. Propose the change with a meaningful commit message.
6. Click "Create Pull Request".

#### **Adding a Thumbnail Screenshot**

When you contribute a room to the directory, including a thumbnail screenshot makes it visually appealing and provides a quick preview of the room. Here are the guidelines for adding screenshots:

##### **Naming Convention**

- Name your screenshot file using the following format: `[RoomName]-thumbnail.[ext]`, where `[RoomName]` is a concise version of your room title and `[ext]` is the file extension based on the image format (e.g., 'community-meetup-thumbnail.png').
- Use dashes (-) instead of spaces, and keep the name lowercase to ensure consistency and compatibility.

##### **Image Specifications**

- **Preferred Dimensions**: Aim for an image size of `1280x720 pixels` (720p). This dimension works well across devices, offering a balance between clarity and file size.
- **Supported Formats**: GitHub supports a range of image formats. For thumbnails, you should use either `JPEG` (.jpg/.jpeg) for photos or complex images, or `PNG` (.png) for images with transparency or simpler graphics.
- **Maximum File Size**: Keep the image file size under `4MB` to ensure quick loading times and to be considerate of those with bandwidth limitations.

##### **Uploading Screenshots**

1. Upload the image to the `thumbnails` folder within the repository. You can do this by navigating to the folder, clicking "Add file" > "Upload files", and then selecting your pre-named image file.
2. Reference the image in the README.md by including it in your room's entry using markdown image syntax: `![Alt text](/thumbnails/[YourImageFileName].[ext])`, replacing `[YourImageFileName].[ext]` with the name of your uploaded file.


### **Step 6: PR Review and Approval**

Wait for the directory maintainers to review your PR. They may merge it, request changes, or reject it if it doesn't fit the project's needs. Remember, each review is a step towards making a valuable contribution. After your PR is merged, it will become part of the project. If rejected, don't be discouraged; review the feedback, and feel free to ask for clarification or submit new contributions in the future.


### Privacy Implications

When adding a room to this directory, it's important to know that the details you share become part of the public record on GitHub. This includes the room's name, description, and URL, along with any other information you provide in your pull request.

Additionally, your git commit includes your name and email address as configured in your local git environment. This could be different from your GitHub profile information. This means that when you make a contribution, your identity and contact information as per your git settings could also be visible alongside the content of your contribution.

Please review the information you're about to share, ensuring it doesn't include anything private or sensitive that you're not comfortable making public. Remember, once submitted, this information can be viewed by anyone and remains accessible even if you later modify or delete it.


By following these guidelines, you help maintain a consistent and professional appearance for the Mozilla Hubs rooms directory.
