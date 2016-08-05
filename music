/**
 * Copyright 2016 Sowlly Xiang
 *
 * www.xn--yetr5d547adqtrxlfkd55f.com 
 */

/**
 * 预载入音乐的提示信息。
 */
var LOADING_MUSICS = "正在载入音乐，请稍后……";

/**
 * 是否预加载所有的音乐。
 */
var PRELOAD_MUSICS = false;

/**
 * 是否自动播放音乐。
 */
var AUTOPLAY = true;

/**
 * 是否乱序随机播放。若为false，则顺序播放音乐。
 */
var SHUFFLE = false;

/**
 * 是否循环播放背景音乐。建议设为true。
 */
var LOOP_MUSICS = true;

/**
 * 背景音乐音量大小。建议设为100。
 */
var MUSIC_VOLUME = 100;

/**
 * 所有背景音乐的总数目。如果要添加删除音乐，请修改此数目。
 */
var MUSIC_COUNT = 1;

/**
 * 播放的背景音乐所在的目录，默认为 "./musics"。
 *
 * 该目录中的音乐必须为MP3格式并以".mp3"为文件名后缀，音乐总数目必须为 MUSIC_COUNT 。
 * 音乐的文件名必须从1开始编号，到 MUSIC_COUNT 为止，即"1.mp3", "2.mp3", ..., "100.mp3".
 */
var MUSIC_DIR = "./musics";

/**
 * 幻灯片播放时背景音乐的URL列表。注意如果SHUFFLE选项为false，则会按照数组的顺序播放音乐。
 */
var MUSICS = [];

// 默认将使用"musics"目录下的所有音乐，按照其文件名顺序播放。
// 默认将使用 MUSIC_DIR 目录下的所有音乐，按照其文件名顺序播放，音乐格式都必须为mp3。
// 如果要增加或减少音乐的数目，请修改 MUSIC_COUNT 的值。
// 当然，也可以直接定义 MUSICS 数组的值，不过那样音乐多了会比较麻烦。
(function() {
  for (var i = 1; i <= MUSIC_COUNT; ++i) {
    MUSICS.push(MUSIC_DIR + "/" + i + ".mp3");
  }
})();
