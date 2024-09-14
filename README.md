My YT Bookmarks

My YT Bookmarks is a simple Chrome extension that allows users to save specific timestamps in YouTube videos for later reference. This can be useful for marking important moments, tutorial sections, or favorite parts of a video for quick access.
Features

    Save timestamps from any YouTube video.
    View saved bookmarks and quickly jump to the saved time.
    Delete bookmarks you no longer need.
    Simple popup interface for managing your bookmarks.

How It Works

    Open any YouTube video.
    Use the extension's interface to add bookmarks for specific timestamps.
    View and manage your bookmarks through the popup, where you can jump directly to the saved timestamp or delete it.

Installation

    Clone or download this repository.
    Open Chrome and go to chrome://extensions/.
    Enable Developer Mode (toggle is in the top-right corner).
    Click Load unpacked and select the folder containing the extension files.
    The extension will now appear in your browser's extension toolbar!

Usage

    Open a YouTube video.
    Click on the My YT Bookmarks icon in the Chrome toolbar.
    Use the popup to:
        Add a bookmark for the current time.
        View a list of saved bookmarks.
        Jump to a saved timestamp by clicking on the bookmark.
        Delete bookmarks you no longer need.

Files Overview

    manifest.json: The configuration file that tells Chrome how to run the extension.
    background.js: The background script that manages saving and loading bookmarks.
    contentScript.js: The script that interacts with YouTube pages, allowing you to capture timestamps.
    popup.html: The user interface for adding, viewing, and managing bookmarks.
    assets/: Folder containing images/icons for the extension (e.g., save, play, delete icons).

Permissions

This extension requires the following permissions:

    storage: To save and retrieve your bookmarks.
    tabs: To interact with the current YouTube tab.
    YouTube access: The extension can read and modify YouTube content to save timestamps.
