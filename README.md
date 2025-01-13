<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahatma Gandhi - Wikipedia</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap');
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', sans-serif;
        }
        body {
            background-color: #f5f5f5;
            color: #202122;
            line-height: 1.6;
        }
        .navbar {
            background-color: #ffffff;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .search-container {
            max-width: 800px;
            margin: 0 auto;
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        .search-box {
            flex: 1;
            padding: 0.8rem 1rem;
            border: 2px solid #ddd;
            border-radius: 25px;
            font-size: 1rem;
            transition: all 0.3s ease;
        }
        .search-box:focus {
            outline: none;
            border-color: #36c;
            box-shadow: 0 0 5px rgba(51,102,204,0.3);
        }
        .search-button {
            padding: 0.8rem 1.5rem;
            background-color: #36c;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .search-button:hover {
            background-color: #447ff5;
        }
        .navigation {
            background-color: #f8f9fa;
            padding: 1rem;
            border-bottom: 1px solid #ddd;
        }
        .nav-links {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .nav-links a {
            color: #36c;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }
       .nav-links a:hover {
            background-color: #eaf3ff;
        }
        .main-content {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .title {
            font-size: 2.5rem;
            color: #202122;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        .media-container {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
            margin-bottom: 2rem;
        }
        .gandhi-image {
            max-width: 500px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .gandhi-image:hover {
            transform: scale(1.02);
        }
\
        .video-container {
            flex: 1;
            min-width: 300px;
            max-width: 500px;
        }
\
        .video-container iframe {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .biography {
            background-color: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            line-height: 1.8;
        }
        .biography a {
            color: #36c;
            text-decoration: none;
        }
        .biography a:hover {
            text-decoration: underline;
        }
        @media (max-width: 768px) {
            .media-container {
                flex-direction: column;
                align-items: center;
            }
            .gandhi-image {
                width: 100%;
                max-width: 400px;
            }
            .video-container {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="search-container">
            <input type="search" class="search-box" placeholder="Search Wikipedia">
            <button class="search-button">Search</button>
        </div>
    </nav>
  <div class="navigation">
        <div class="nav-links">
            <div class="left-links">
                <a href="#">ARTICLE</a>
                <a href="https://en.wikipedia.org/wiki/Talk:Mahatma_Gandhi">TALK</a>
            </div>
            <div class="right-links">
                <a href="#">READ</a>
                <a href="https://en.wikipedia.org/w/index.php?title=Mahatma_Gandhi&action=edit">VIEW SOURCE</a>
                <a href="https://en.wikipedia.org/w/index.php?title=Mahatma_Gandhi&action=history">VIEW HISTORY</a>
                <a href="#">TOOLS</a>
            </div>
        </div>
    </div>
    <main class="main-content">
        <h1 class="title">Mahatma Gandhi</h1>
        <div class="media-container">
            <img class="gandhi-image" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Mahatma-Gandhi%2C_studio%2C_1931.jpg/800px-Mahatma-Gandhi%2C_studio%2C_1931.jpg" alt="Mahatma Gandhi">
            <div class="video-container">
                <iframe height="315" src="https://www.youtube.com/embed/nO_TRBPRids?si=RxpqjXfFyw5vidTO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>
        <article class="biography">
            <p><strong>Mohandas Karamchand Gandhi</strong> (<a href="https://en.wikipedia.org/wiki/ISO_15919">ISO</a>: <em>Mōhanadāsa Karamacaṁda Gāṁdhī</em>; 2 October 1869 – 30 January 1948) was an <a href="#">Indian lawyer</a>, <a href="https://en.wikipedia.org/wiki/Nationalism#Anti-colonial">anti-colonial nationalist</a>, and <a href="https://en.wikipedia.org/wiki/Political_ethics">political ethicist</a> who employed <a href="https://en.wikipedia.org/wiki/Nonviolent_resistance">nonviolent resistance</a> to lead the successful <a href="https://en.wikipedia.org/wiki/Indian_independence_movement">campaign for India's independence</a> from <a href="https://en.wikipedia.org/wiki/British_Raj">British rule</a>.</p> 
            <p>He inspired movements for <a href="https://en.wikipedia.org/wiki/Civil_rights_movements">civil rights</a> and freedom across the world. The honorific Mahātmā (from Sanskrit 'great-souled, venerable'), first applied to him in <a href="https://en.wikipedia.org/wiki/Union_of_South_Africa">South Africa</a> in 1914, is now used throughout the world.</p>
            <p>Born and raised in a <a href="https://en.wikipedia.org/wiki/Hindus">Hindu</a> family in coastal <a href="https://en.wikipedia.org/wiki/Gujarat">Gujarat</a>, Gandhi trained in the law at the <a href="https://en.wikipedia.org/wiki/Inner_Temple">Inner Temple</a> in London and was <a href="https://en.wikipedia.org/wiki/Call_to_the_bar">called to the bar</a> in June 1891, at the age of 22. After two uncertain years in India, where he was unable to start a successful law practice, Gandhi moved to South Africa in 1893 to represent an Indian merchant in a lawsuit. He went on to live in South Africa for 21 years. There, Gandhi raised a family and first employed nonviolent resistance in a campaign for civil rights.</p>    
            <p>In 1915, aged 45, he returned to India and soon set about organising peasants, farmers, and urban labourers to protest against discrimination and excessive land-tax.</p>
        </article>
    </main>
</body>
</html>
