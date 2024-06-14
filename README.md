# Welcome Messages for FHIR Zulip Channels

This repository contains markdown files that correspond to welcome messages for Zulip channels. When a user joins a channel, they will automatically receive a private message with the contents of the corresponding markdown file.

## Creating or Updating a Welcome Message

To create or update a welcome message for a Zulip channel, follow these steps:

1. Identify the channel ID and name from the Zulip channel URL. The URL format is:
   ```
   https://chat.fhir.org/#narrow/stream/<channel_id>-<channel_name>
   ```
   For example, if the channel URL is `https://chat.fhir.org/#narrow/stream/179280-fhir.2Finfrastructure-wg`, the channel ID is `179280` and the channel name is `fhir.2Finfrastructure-wg`.

2. In this repository, create a new markdown file or edit an existing one. The file should be named using the format:
   ```
   <channel_id>-<channel_name>.md
   ```
   For example, for the channel with ID `179280` and name `fhir.2Finfrastructure-wg`, the file would be named `179280-fhir.2Finfrastructure-wg.md`.

3. Write the welcome message in the markdown file. You can use standard markdown formatting to structure and style the content.

4. Commit your changes and submit a pull request to the `main` branch of this repository.

5. Once your pull request is merged, the bot will detect the changes within 5 minutes and start sending the updated welcome message to new users who join the corresponding Zulip channel.

## Guidelines for Effective Welcome Messages

When creating welcome messages for workgroup channels, consider including the following information to help new members get started:

1. A brief introduction to the workgroup and its purpose.
2. Links to important resources, such as:
   - Workgroup's Confluence page
   - Meeting minutes or notes
   - Zoom call calendar or meeting schedule
   - Relevant documentation or specifications
3. Instructions on how to participate in the workgroup, such as:
   - How to join meetings or calls
   - How to contribute to discussions or projects
   - Who to contact for specific questions or assistance
4. Any other relevant information or guidelines specific to the workgroup.

Keep the welcome message concise and organized, using clear headings and bullet points to make it easy to read and navigate. Use friendly and welcoming language to encourage engagement and participation.

Remember to keep the welcome messages up to date as the workgroup's resources and processes evolve over time.

By providing informative and welcoming messages, we can help new members feel welcomed and equipped to contribute effectively to the workgroup's activities.
