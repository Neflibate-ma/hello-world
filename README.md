# hello-world
此存储库用于练习Githup流

public class DM {
    public static void main(String[] args) {
randomcall();
    }

    public static void randomcall() {
        String[]names={"单江啸","冯柯","祖晨阳","常文勇","马佳帅","吕在硕"};
        int index=(int)(Math.random()*names.length);

        String name=names[index];
        System.out.println(
                name+"去买饭"
        );;



    }


