# Project1
This is project1
<!DOCTYPE html>
<html>
<head>
    <title>Social Media Post</title>
    <style>
        /* Inline CSS for simplicity, but it's recommended to use an external stylesheet */
        .post {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            max-width: 500px;
            background-color: #fff;
        }

        .post-header {
            font-weight: bold;
        }

        .post-content {
            margin-top: 10px;
        }

        .post-actions {
            margin-top: 10px;
        }

        .like-button, .comment-button, .share-button {
            background-color: #007BFF;
            color: #fff;
            padding: 5px 10px;
            border: none;
            margin-right: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="post">
        <div class="post-header">
            <img src="user-profile-image.jpg" alt="User Profile Image" width="50" height="50"> John Doe
        </div>
        <div class="post-content">
            <p>This is the content of the social media post. It can be quite long and include text, images, or videos.</p>
        </div>
        <div class="post-actions">
            <button class="like-button">Like</button>
            <button class="comment-button">Comment</button>
            <button class="share-button">Share</button>
        </div>
    </div>

    <script>
        // JavaScript can be added here for interactivity if needed
        // For example, you can use JavaScript to handle like, comment, and share actions.
        document.querySelector('.like-button').addEventListener('click', function() {
            alert('You liked this post.');
        });

        document.querySelector('.comment-button').addEventListener('click', function() {
            alert('You commented on this post.');
        });

        document.querySelector('.share-button').addEventListener('click', function() {
            alert('You shared this post.');
        });
    </script>
</body>
</html>
