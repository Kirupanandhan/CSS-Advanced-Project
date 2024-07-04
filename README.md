### Create a simplified clone of Dribbble landing page.
#### Project: Simplified Clone of Dribbble Landing Page
Objective
To create a simplified clone of the Dribbble landing page using HTML, CSS. This project will focus on replicating the main visual and functional elements of the page, providing a clean and responsive design.


#### dribble.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design Gallery</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="logo">
            <a href="#">Dribbble</a>
        </div>
        <nav>
            <a href="#">Shots</a>
            <a href="#">Designers</a>
            <a href="#">Teams</a>
            <a href="#">Community</a>
            <a href="#">Jobs</a>
        </nav>
        <div class="auth-buttons">
            <button>Sign up</button>
            <button>Sign in</button>
        </div>
    </header>
    <main>
        <div class="intro">
            <p>What are you working on? Dribbble is show and tell for designers.</p>
            <button>Learn more</button>
            <button>Sign up</button>
        </div>
        <div class="filter-bar">
            <select>
                <option>Popular</option>
                <option>Newest</option>
                <option>Following</option>
            </select>
            <select>
                <option>Shots</option>
                <option>Designs</option>
                <option>Animations</option>
            </select>
            <select>
                <option>Now</option>
                <option>Past Week</option>
                <option>Past Month</option>
            </select>
        </div>
        
        <section class="shots-gallery">
            <!-- Repeat this block for each shot -->
            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15417820/file/original-ec3016842f085f024f3769c55d8f878d.jpg?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Krestovskaya Anna</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>
            <!-- Add more shot items as needed -->
            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15411410/file/original-805da8f55afce317055cd4b4701cbfdd.jpg?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">MUTI</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15412897/file/still-ad0d89a061092b183f2bf9c5ddb10b43.gif?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">ILLO</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15408692/file/original-4503e63acff01eb76c603e984b5a9607.png?crop=0x0-1600x1200&resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Alfrey Davilla | vaneltia</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15408505/file/original-f459565f3270a3e2ec44a4303ed58709.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Rw Studio</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15402960/file/still-5204ff6252fc58b8b3d273cd632b9c81.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Nixtio
                    </p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15412830/file/original-31f5db86e8d52e86d5ae1239920c81da.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Stevan Rodic</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15416110/file/original-27e6bd9054c968b243768900cd130ad1.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Alexandra Zutto</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15406497/file/original-53569c16886eb7e07f74604be4793c82.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Ramotion
                    </p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15407734/file/original-e6776b90099f2ea7cb86482ecad9d0b5.jpg?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Jordan Jenkins
                    </p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15390292/file/original-8bd0ef410b47ec69aa70b19c3cefc03a.jpg?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Coric Design</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15410337/file/original-df95eeae8221c6048bafdc00597c5c34.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Gotoinc
                    </p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15406497/file/original-53569c16886eb7e07f74604be4793c82.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Famous</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15403398/file/original-7d52b232c0da6d11bea102a7d96e0727.png?crop=0x0-3501x2626&resize=400x300&vertical=center
" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">HALO LAB</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15411244/file/original-da84c77fa457dab5f3022bb449c906d6.jpg?crop=0x0-6667x5000&resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Lucas Fields</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15410840/file/original-2a3d36b981da9d49e0799bcb4d9f3683.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">tubik</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15412564/file/original-bb486cc359b5d1915cd1d9784a59693b.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Famous</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15404984/file/original-713bb53fe99dba3673bf3977ac3fd98b.jpg?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Tyler Pate</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15312803/file/original-54feaa24aacf1acebbf65173643370a7.jpg?crop=76x29-1319x962&resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Folio Illustration Agency</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15404368/file/original-5b673d27c5bbb85bfe54d54f0a1b7273.png?resize=400x300&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Lucian Radu</p>
                    <div class="shot-meta">
                        <span><i class="fas fa-eye"></i>4044</span>
                        
                        <span><i class="fas fa-heart"></i> 290</span>
                    </div>
                </div>
            </div>

    </main>
</body>
</html>

```
#### style.css
```
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
    }

    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px;
        background-color: #333;
        color: #fff;
    }

    .logo a {
        font-size: 24px;
        color: #fff;
        text-decoration: none;
        font-family: cursive;
    }

    nav a {
        margin: 0 10px;
        text-decoration: none;
        color: #fff;
    }

    .auth-buttons button {
        margin: 0 5px;
        padding: 10px 20px;
        border: none;
        background-color: #ff0080;
        color: #fff;
        cursor: pointer;
    }

    .intro {
        text-align: center;
        padding: 20px;
        background-color: #222;
        color: #fff;
    }

    .intro button {
        margin: 10px;
        padding: 10px 20px;
        border: none;
        background-color: #ff0080;
        color: #fff;
        cursor: pointer;
    }

    .filter-bar {
        display: flex;
        justify-content: center;
        padding: 10px;
        background-color: #fff;
    }

    .filter-bar select {
        margin: 0 10px;
        padding: 10px;
        border: 1px solid #ccc;
        background-color: #f4f4f4;
        cursor: pointer;
    }

    .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        padding: 20px;
        background-color: #f4f4f4;
    }

    .gallery-item {
        position: relative;
        margin: 10px;
    }

    .gallery-item img {
        width: 200px;
        height: 200px;
        border-radius: 10px;
        transition: transform 0.3s ease;
    }

    .gallery-item:hover img {
        transform: scale(1.1);
    }

    .overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.6);
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        opacity: 0;
        transition: opacity 0.3s ease;
        border-radius: 10px;
    }

    .gallery-item:hover .overlay {
        opacity: 1;
    }
    gallery-header {
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .filter-options {
        display: flex;
        gap: 10px;
    }

    .shots-gallery {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        gap: 15px;
        padding: 20px;
    }

    .shot-item {
        background-color: white;
        border-radius: 5px;
        overflow: hidden;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        position: relative;
        transition: transform 0.3s ease;
    }

    .shot-item:hover {
        transform: translateY(-5px);
    }

    .shot-item img {
        width: 100%;
        display: block;
    }

    .shot-info {
        padding: 10px;
        text-align: center;
    }

    .shot-title {
        font-weight: bold;
        margin: 0;
    }

    .shot-meta {
        display: flex;
        justify-content: space-around;
        padding-top: 5px;
    }

```
### OUTPUT:
![image](https://github.com/Kirupanandhan/CSS-Advanced-Project/assets/94386222/4e2abb73-9837-4362-9972-0bb29ac2efaa)
