package comitheima.Oneday_Test;

/**
 * 这个字符串中有多少个字母
 */

public class Test02 {
    public static void main(String[] args) {
        getNumberSum("abc我爱你ABC12345");
    }

    /**
     * A-Z在ASCll表中的码值：97 -- 122
     * a-z在ASCll表中的码值：65 -- 90
     * 0-9在ASCll表中的码值：48 -- 57
     * @param arr
     */
    public static void getNumberSum(String arr){
        int sum = 0;
        char[] chars = arr.toCharArray();
        for (int i = 0; i < chars.length; i++) {
            if (chars[i] >= 65 && chars[i] <= 90 ||
            chars[i] >= 97 && chars[i] <= 122 ||
            chars[i] >= 48 && chars[i] <= 57){
                System.out.print("这些字母是：" + chars[i]);
                sum++;
            }
        }
        System.out.println("总共有:" + sum + "个字母和数字");
    }
}
