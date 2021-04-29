# Commands

## Setting Your Birthday

Setting your birthday very easy! Just run the command below, replacing `MM/DD` with your birthday. For example if your birthday was May 3rd you would run `b!setbday 05/03`

```
b!setbday MM/DD
```

## Setting Others Birthdays

Settings others birthdays is also very easy, just mention them when running the command below. So if I wanted to set my friend Bob's Birthday to June 23 I would run `b!setbday @Bob 06/23`

```text
b!setbday @user MM/DD
```

## Setting the Birthday Channel

{% hint style="danger" %}
If you do not set the birthday channel birthday will **not** be announced!
{% endhint %}

To set the birthday channel just run the command below, replacing `#channel` with the channel you want birthdays to be announced in.

```text
b!channel #channel
```

## Setting the Birthday Message

{% hint style="info" %}
If you do not set a birthday message it will default to "Happy Birthday {user} hope you have a great day :\)"
{% endhint %}

To set the birthday message just run the command below but replace `<message>` with the message you would like to use to wish people a happy birthday. Use `{user}` to mention the user in that message. For example if I wanted the birthday announcement message to be "Happy Birthday @User" I would run `b!bdaymessage Happy Birthday {user}`.

```text
b!message <message>
```

