<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Michelle Dawn Wright | Official Portfolio</title>
    <style>
        :root {
            --bg-color: #0f1117;
            --card-bg: #1a1d24;
            --accent-color: #7c4dff;
            --text-color: #f0f2f5;
            --muted-color: #a0a5b5;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 60px 20px 40px;
            max-width: 800px;
            margin: 0 auto;
        }

        h1 {
            font-size: 2.8rem;
            margin-bottom: 15px;
            letter-spacing: -0.5px;
            color: #ffffff;
        }

        .bio {
            font-size: 1.15rem;
            color: var(--muted-color);
            max-width: 650px;
            margin: 0 auto;
        }

        main {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }

        section {
            margin-bottom: 60px;
        }

        h2 {
            font-size: 1.8rem;
            margin-bottom: 25px;
            border-bottom: 2px solid var(--accent-color);
            display: inline-block;
            padding-bottom: 5px;
        }

        /* Video Section Grid */
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
        }

        .video-card {
            background-color: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        .card-info {
            padding: 15px 20px;
        }

        /* Audio Tracks List */
        .audio-list {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .audio-card {
            background-color: var(--card-bg);
            padding: 20px;
            border-radius: 10px;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        audio {
            width: 100%;
            margin-top: 5px;
        }

        /* Gallery Grid */
        .image-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }

        .image-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.2s ease;
        }

        .image-card img:hover {
            transform: scale(1.02);
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            color: var(--muted-color);
            font-size: 0.9rem;
            border-top: 1px solid #2a2d35;
        }
    </style>
</head>
<body>

    <header>
        <h1>Michelle Dawn Wright</h1>
        <p class="bio">
            Welcome to my creative portfolio. This is the central hub for my work—a curated showcase of original compositions, visual media, and digital art created personally and enhanced through collaborative AI tools.
        </p>
    </header>

    <main>

        <!-- Featured Music Videos Section -->
        <section id="videos">
            <h2>Featured Videos</h2>
            <div class="video-grid">
                
                <!-- Video Item 1 -->
                <div class="video-card">
                    <div class="video-container">
                        <!-- Replace YOUTUBE_VIDEO_ID with your YouTube video ID code -->
                        <iframe src="https://www.youtube.com/embed/YOUTUBE_VIDEO_ID" title="Featured Video" allowfullscreen></iframe>
                    </div>
                    <div class="card-info">
                        <h3>Track / Video Title 1</h3>
                    </div>
                </div>

                <!-- Video Item 2 -->
                <div class="video-card">
                    <div class="video-container">
                        <iframe src="https://www.youtube.com/embed/YOUTUBE_VIDEO_ID" title="Featured Video" allowfullscreen></iframe>
                    </div>
                    <div class="card-info">
                        <h3>Track / Video Title 2</h3>
                    </div>
                </div>

            </div>
        </section>

        <!-- Audio Tracks Section -->
        <section id="music">
            <h2>Music & Audio</h2>
            <div class="audio-list">
                
                <div class="audio-card">
                    <h3>Song Title 1</h3>
                    <!-- Replace with the file path to your MP3 audio file -->
                    <audio controls src="audio/your-track-1.mp3"></audio>
                </div>

                <div class="audio-card">
                    <h3>Song Title 2</h3>
                    <audio controls src="audio/your-track-2.mp3"></audio>
                </div>

            </div>
        </section>

        <!-- Artwork & Images Section -->
        <section id="gallery">
            <h2>Visual Art & Photography</h2>
            <div class="image-grid">
                
                <div class="image-card">
                    <img src="YOUR_IMAGE_LINK_HERE" alt="Digital Artwork 1">
                </div>

                <div class="image-card">
                    <img src="images/art-piece-2.jpg" alt="Digital Artwork 2">
                </div>

            </div>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 Michelle Dawn Wright. All rights reserved.</p>
    </footer>

</body>
</html>
