```math
\ce{$\unicode[ 'GoombaFont';

        body {
            font-family: 'GoombaFont', sans-serif;
        }

        .background-image {
            color: red;
            pointer-events: none;
            z-index: -10;
            position: fixed;
            top: 0;
            left: 0;
            height: 100vh;
            width: 130vw;
            opacity: 0.5;
            background: url('https://raw.githubusercontent.com/klywenc/klywenc/main/tenor.gif') no-repeat center center;
            background-size: cover;
        }

        .rotating-image {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 200px;
            height: 200px;
            background: url('https://raw.githubusercontent.com/klywenc/klywenc/main/tenor.gif') no-repeat center center;
            background-size: cover;
            animation: rotate 5s infinite linear;
        }

        @keyframes rotate {
            0% {
                transform: translate(-50%, -50%) rotateY(0deg);
            }
            100% {
                transform: translate(-50%, -50%) rotateY(360deg);
            }
        }]{x0000}$}
