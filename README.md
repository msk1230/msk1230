### Hi there 👋
我是马寿康，今年20岁

就读于淄博职业学院，预计2021年毕业

我学习的课程有java Photoshop pythen c# Android移动应用开发基础等

我的邮箱是395823204@qq.com欢迎大家给我发邮件

我的家乡在美丽的甘肃酒泉

我的爱好是打游戏，看小说，跑步，听音乐

在我的幻想中的计算机专业，应该是能够了解计算机的基础知识，精通计算机语言，当然，还要包括会修电脑

我选计算机专业的原因完全是因为我兴趣和个人爱好，在过去的学习中，我收获了许多的专业知识，基本能够满足我对计算机专业的期待，因为他比我想象中的还要难，，就我个人来说，我还是喜欢计算机的，但他并不是我擅长的领域，因为我还并没有学精通他。

我现在所掌握的技能还属于初级阶段，但我对他们很有兴趣，对于我自己来说，还缺少持续学习的能力

我做过的最有意思的课程作业是大一第二学期的“学工系统”  通过这次的作业，我学习到了许多，也找到了许多学习中的不足与漏洞，这次的作业更像是一次查漏补缺。

在这门课程中，我希望能够学到更多的专业知识，能够对软件技术有更多的了解，能够对我将来的工作与生活有很大的帮助。

通过了解别人选择计算机的原因，我觉得我的觉悟还没有他们的高，我更应该好好学习，去努力的奋斗，同时，也明白，在课堂中一定要认真听讲，将听讲视为一种能力，大学中的没一门课程都有他设立的意义，，在课堂中要能跟上老师的节奏，要聚精会神的听讲。

public class msk {
    public static void main(String[] args) {
        int[] numbers=new int[]{1,5,8,2,3,9,4};
        int i,j;
        for(i=0;i<numbers.length-1;i++)
        {
            for(j=0;j<numbers.length-1-i;j++)
            {
                if(numbers[j]>numbers[j+1])
                {
                    int temp=numbers[j];
                    numbers[j]=numbers[j+1];
                    numbers[j+1]=temp;
                }
            }
        }
        System.out.println("从小到大排序后的结果是:");
        for(i=0;i<numbers.length;i++)
            System.out.print(numbers[i]+" ");
    }
}



<!--
**msk1230/msk1230** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
