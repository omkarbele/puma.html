# puma.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mynrta</title>
    <style>
        * {
            font-family: Assistant, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
            padding: 0;
            margin: 0;
        }

        #screen {
            width: 100%;
            /* height: 400px;
            border: 2px solid yellow; */
        }

        #navbar {
            width: 100%;
            height: 400px;
            background-image: url('./babel.png');
        }

        #body {
            width: 100%;
            /* border: 2px solid red; */
            display: flex;
            justify-content: space-around;
        }

        #body>div:nth-child(1) {
            width: 15%;
        }

        #body>div:nth-child(2) {
            width: 81%;
            /* border: 2px solid black; */
        }

        #body>div:nth-child(1)>div {
            border-bottom: 1px solid black;
            margin-left: 20px;
        }

        #body>div:nth-child(1)>div>h4 {
            margin-top: 15px;
            margin-bottom: 15px;
        }

        #body>div:nth-child(1)>div>input,
        label {
            margin-bottom: 10px;
        }

        #products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        #products>div {
            width: 18%;
            height: 370px;
            margin-bottom: 20px;
        }

        #products>div:hover {
            border: 1px solid black;

        }

        #products>div>img {
            width: 100%;
            height: 75%;
        }

        #products>div>h4,
        p {
            margin-left: 20px;
            margin-bottom: 4px;
        }

        #products>div>h4:nth-child(2) {
            color: red;
        }
    </style>
</head>

<body>
    <div id="screen">
        <div id="navbar">
            Hello world...
        </div>
        <div id="body">
            <div>
                <div>
                    <h4>CATEGORIES</h4>
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label>
                </div>
                <div>
                    <h4>BRAND</h4>
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label>
                </div>
                <div>
                    <h4>PRICE</h4>
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label><br />
                    <input type="checkbox" />
                    <label>Tshirts(96164)</label>
                </div>
            </div>
            <div id="products">
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma - tagert</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
                <div>
                    <img
                        src="https://assets.myntassets.com/h_720,q_90,w_540/v1/assets/images/18982090/2022/7/19/e618a91f-c4a3-48ea-9ea0-0d105025b5de1658232227623-Manchester-City-FC--Home-Jersey-Replica-2891658232227240-1.jpg" />
                    <h4>Puma</h4>
                    <p>Thsirt</p>
                    <h4>1500</h4>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
