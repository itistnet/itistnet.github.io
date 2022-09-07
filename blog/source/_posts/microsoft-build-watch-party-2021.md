---
title: MVP Microsoft Build Watch Party (ASP.NET Korea)
date: 2021-06-04 01:14:30
tags: [MSBuild, MicsoroftBuildWatchParty, MVP, MicrosoftBuild]
categories: [새소식]
---

![](/images/microsoft-build-watch-party-2021/01.png)

이번 Build 2021 행사에서 아래 세션에 관심을 가지신 분들이 많을 것 같은데요.
온라인으로 함께 모여서 세션 영상도 보고, 이런저런 이야기도 나누는 시간을 가져보려고 합니다.

수정 테스트

"The future of modern application development with .NET"
(https://mybuild.microsoft.com/sessions/76ebac39-517d-44da-a58e-df4193b5efa9)

유튜브 영상도 제공됩니다.
https://youtu.be/2Ky28Et3gy0

{% youtube 2Ky28Et3gy0 %}

<br>

- 진행 순서
  - 소개, 인사, 근황 토크(10분)
  - 세션 영상 시청(30분)
  - Q&A, 자유 토론, 마무리(20분+)
- 일시 : 2021.06.04.금 오후 5시 ~ 6시(1시간)
- 참여 링크(Microsoft Teams) : https://bit.ly/3goieZt

온라인 미팅에 익숙하지 않은 분이라도 전혀 부담가질 필요 없으니 오랜만에 모임하는 기분으로 가볍게 참여해 주시면 좋겠습니다.

# H1H1H1H1H1H1H1H1H1H1H1

## H2H2H2H2H2H2H2H2H2H2H2

### H3H3H3H3H3H3H3H3H3H3H3

> 블럭인용문자
>
> > 블럭인용문자2
> >
> > > 블럭인용문자3

소스 코드는 이렇게

```c#
void FindRoot(Node node, Action<Node> processNode)
{
    for (var current = node; current != null; current = current.Parent)
    {
        processNode(current);
    }
}

public void PrintMessage(string message)
{
    if (!string.IsNullOrWhiteSpace(message))
    {
        Console.WriteLine($"{DateTime.Now}: {message}");
    }
}
```
