# e-business

运行main.py即可
默认端口：8080

url: /seeds
method : POST
传入格式：JSON
{
  'text' : '传入的话'
}

返回格式：JSON
{
    "status": 200,
    "keyword": [
        "这是",
        "一句",
        "话",
        "测试"
    ],
    "data": {
        "这是": {
            "intermediate": {
                "0": {
                    "name": "时代",
                    "frequency": 0.071,
                    "compete": 0.956
                },
                "1": {
                    "name": "歌词",
                    "frequency": 0.071,
                    "compete": 0.956
                }
            },
            "compete": {
                "0": {
                    "name": "时代",
                    "frequency": 0.071,
                    "compete": 0.956
                },
                "1": {
                    "name": "身体",
                    "frequency": 0.071,
                    "compete": 0.952
                }
            }
        }  
    }
}
