# AI Agent Framework များကို စူးစမ်းလေ့လာခြင်း

[![AI Agent Framework များကို စူးစမ်းလေ့လာခြင်း](./images/lesson-2-thumbnail.png)](https://youtu.be/ODwF-EZo_O8?si=1xoy_B9RNQfrYdF7)

> _(ဤသင်ခန်းစာ၏ ဗီဒီယိုကို ကြည့်ရှုရန် အထက်ပါပုံကို နှိပ်ပါ)_

# AI Agent Framework များကို စူးစမ်းလေ့လာခြင်း

AI Agent Framework များသည် AI အေးဂျင့်များ၏ ဖန်တီးမှု၊ အသုံးချမှု နှင့် စီမံခန့်ခွဲမှုတို့ကို ရိုးရှင်းစေရန် ရည်ရွယ်၍ တီထွင်ထားသော ဆော့ဖ်ဝဲလ် ပလပ်ဖောင်းများဖြစ်သည်။ ဤ Framework များသည် developer များအတွက် ရှုပ်ထွေးသော AI စနစ်များ ဖွံ့ဖြိုးတိုးတက်စေရာတွင် လမ်းကြောင်းပြပေးနိုင်သည့် ကြိုတင်တည်ဆောက်ထားသော အစိတ်အပိုင်းများ၊ abstract များနှင့် ကိရိယာများကို ပံ့ပိုးပေးပါသည်။

ဤ Framework များသည် AI Agent ဖွံ့ဖြိုးမှုတွင် တွေ့ကြုံရသော ယေဘုယျ စိန်ခေါ်မှုများအတွက် သတ်မှတ်ထားသော ချဉ်းကပ်နည်းများကို ပံ့ပိုးပေးခြင်းဖြင့် developer များအား ၎င်းတို့၏ အပလီကေးရှင်းများ၏ ထူးခြားသော အင်္ဂါရပ်များအပေါ် အာရုံစိုက်နိုင်စေပါသည်။ ၎င်းတို့သည် AI စနစ်များ တည်ဆောက်ရာတွင် တိုးချဲ့နိုင်မှု၊ အသုံးဝင်နိုင်မှုနှင့် ထိရောက်မှုတို့ကို မြှင့်တင်ပေးပါသည်။

## မိတ်ဆက်

ဤသင်ခန်းစာတွင် အောက်ပါအချက်များကို ခြုံငုံ၍ လေ့လာမည်ဖြစ်သည်-

- AI Agent Framework များဆိုသည်မှာ အဘယ်နည်း နှင့် ၎င်းတို့သည် developer များအား မည်သည့်အရာများ အောင်မြင်စေနိုင်သနည်း?
- အဖွဲ့များသည် ၎င်းတို့၏ agent များ၏ စွမ်းရည်များကို လျင်မြန်စွာ prototype တည်ဆောက်ခြင်း၊ ပြန်လည်ပြင်ဆင်ခြင်း နှင့် မြှင့်တင်ခြင်းအတွက် မည်သို့အသုံးပြုနိုင်မည်နည်း?
- Microsoft <a href="https://aka.ms/ai-agents/autogen" target="_blank">AutoGen</a>၊ <a href="https://aka.ms/ai-agents-beginners/semantic-kernel" target="_blank">Semantic Kernel</a> နှင့် <a href="https://aka.ms/ai-agents-beginners/ai-agent-service" target="_blank">Azure AI Agent Service</a> တို့မှ ဖန်တီးထားသော framework များနှင့် ကိရိယာများအကြား ကွာခြားချက်များမှာ မည်သည့်အရာများနည်း?
- ကျွန်ုပ်၏ လက်ရှိ Azure ecosystem ကိရိယာများကို တိုက်ရိုက် ပေါင်းစပ်နိုင်သလား၊ သို့မဟုတ် သီးခြား ဖြေရှင်းနည်းများ လိုအပ်သလား?
- Azure AI Agents service ဆိုသည်မှာ အဘယ်နည်း နှင့် ၎င်းသည် ကျွန်ုပ်အား မည်သို့ အကူအညီပေးနေသနည်း?

## သင်ခန်းစာ ရည်မှန်းချက်များ

ဤသင်ခန်းစာ၏ ရည်မှန်းချက်များမှာ သင်အား အောက်ပါအရာများကို နားလည်စေရန်ဖြစ်သည်-

- AI ဖွံ့ဖြိုးမှုတွင် AI Agent Framework များ၏ အခန်းကဏ္ဍ
- စွမ်းဆောင်ရည်မြင့်မားသော agent များ တည်ဆောက်ရန် AI Agent Framework များကို မည်သို့ အသုံးချရမည်နည်း
- AI Agent Framework များမှ လုပ်ဆောင်နိုင်စေသော အဓိက စွမ်းဆောင်ရည်များ
- AutoGen၊ Semantic Kernel နှင့် Azure AI Agent Service တို့အကြား ကွာခြားချက်များ

## AI Agent Framework များသည် အဘယ်နည်း နှင့် developer များအား မည်သည့်အရာများ လုပ်ဆောင်နိုင်စေသနည်း?

သမာရိုးကျ AI Framework များသည် သင်၏ အပလီကေးရှင်းများတွင် AI ကို ပေါင်းစပ်ရာတွင် အကူအညီပေးနိုင်ပြီး ဤအပလီကေးရှင်းများကို အောက်ပါနည်းလမ်းများဖြင့် ပိုမိုကောင်းမွန်စေနိုင်သည်-

- **စိတ်ကြိုက်ပြင်ဆင်မှု (Personalization)**: AI သည် အသုံးပြုသူ၏ အပြုအမူများနှင့် နှစ်သက်မှုများကို ခွဲခြမ်းစိတ်ဖြာ၍ စိတ်ကြိုက်အကြံပြုချက်များ၊ အကြောင်းအရာများနှင့် အတွေ့အကြုံများကို ပံ့ပိုးပေးနိုင်သည်။
ဥပမာ- Netflix ကဲ့သို့သော streaming service များသည် ကြည့်ရှုမှု သမိုင်းအပေါ် အခြေခံ၍ ရုပ်ရှင်များနှင့် ရှိုးများကို အကြံပြုရန် AI ကို အသုံးပြုကြပြီး အသုံးပြုသူ၏ စိတ်ဝင်စားမှုနှင့် ကျေနပ်မှုကို မြှင့်တင်ပေးသည်။

- **အလိုအလျောက်လုပ်ဆောင်မှုနှင့် ထိရောက်မှု**: AI သည် ထပ်ခါတလဲလဲ လုပ်ရသော အလုပ်များကို အလိုအလျောက်လုပ်ဆောင်ခြင်း၊ လုပ်ငန်းစဉ်များကို ချောမွေ့စေခြင်းနှင့် လုပ်ငန်းဆောင်ရွက်မှု ထိရောက်မှုကို မြှင့်တင်ခြင်းများ လုပ်ဆောင်နိုင်သည်။
ဥပမာ- ဖောက်သည်ဝန်ဆောင်မှု အပလီကေးရှင်းများသည် သာမန် မေးမြန်းမှုများကို ကိုင်တွယ်ရန် AI-စွမ်းအား chatbot များကို အသုံးပြုကြပြီး တုံ့ပြန်ချိန်ကို လျှော့ချကာ ပိုမိုရှုပ်ထွေးသော ပြဿနာများအတွက် လူ့အေးဂျင့်များအား အချိန်ပိုမိုရရှိစေသည်။

- **အဆင့်မြှင့်တင်ထားသော အသုံးပြုသူ အတွေ့အကြုံ**: AI သည် အသံမှတ်သားခြင်း၊ ဘာသာစကားများ လုပ်ဆောင်ခြင်းနှင့် ကြိုတင်ခန့်မှန်းထားသော စာသားများကဲ့သို့သော ထိုးထွင်းသော အင်္ဂါရပ်များကို ပံ့ပိုးပေးခြင်းဖြင့် အသုံးပြုသူ၏ အတွေ့အကြုံကို ပိုမိုကောင်းမွန်စေနိုင်သည်။
ဥပမာ- Siri နှင့် Google Assistant ကဲ့သို့သော virtual assistant များသည် အသံအမိန့်များကို နားလည်ပြီး တုံ့ပြန်ရန် AI ကို အသုံးပြုကြသည်၊ ၎င်းသည် အသုံးပြုသူများအတွက် ၎င်းတို့၏ စက်ပစ္စည်းများနှင့် ပိုမိုလွယ်ကူစွာ အပြန်အလှန်ဆက်သွယ်နိုင်စေသည်။

### ဤအရာများ အားလုံးသည် အလွန်ကောင်းမွန်ကြောင်း ထင်ရသည်၊ ထို့ကြောင့် AI Agent Framework လိုအပ်ရခြင်းမှာ အဘယ်ကြောင့်နည်း?

AI Agent Framework များသည် AI Framework များထက် ပိုမိုအရေးကြီးသော အရာတစ်ခုကို ကိုယ်စားပြုသည်။ ၎င်းတို့သည် သီးခြားရည်မှန်းချက်များ အောင်မြင်ရရှိရန် အသုံးပြုသူများ၊ အခြား agent များနှင့် ပတ်ဝန်းကျင်တို့နှင့် အပြန်အလှန်ဆက်သွယ်နိုင်သော ထိုးထွင်းသော agent များ ဖန်တီးခြင်းကို ဖြစ်နိုင်စေရန် ရည်ရွယ်တီထွင်ထားသည်။ ဤ agent များသည် အလိုအလျောက် အပြုအမူများကို ပြသနိုင်ကြပြီး ဆုံးဖြတ်ချက်များ ချမှတ်နိုင်သလို ပြောင်းလဲနေသော အခြေအနေများနှင့်လည်း လိုက်လျောညီထွေ ဖြစ်နိုင်ကြသည်။ AI Agent Framework များမှ လုပ်ဆောင်နိုင်စေသော အဓိက စွမ်းဆောင်ရည်အချို့ကို လေ့လာကြည့်ကြပါစို့-

- **Agent များ၏ ပူးပေါင်းဆောင်ရွက်မှုနှင့် ညှိနှိုင်းမှု**: ရှုပ်ထွေးသော အလုပ်များကို ဖြေရှင်းရန် ပူးပေါင်းလုပ်ဆောင်နိုင်သော၊ ဆက်သွယ်နိုင်သော နှင့် ညှိနှိုင်းနိုင်သော မျိုးစုံသော AI agent များ ဖန်တီးခြင်းကို ဖြစ်နိုင်စေသည်။

- **အလုပ်လုပ်ငန်း အလိုအလျောက်လုပ်ဆောင်မှုနှင့် စီမံခန့်ခွဲမှု**: agent များအကြား အဆင့်ပေါင်းများစွာရှိသော လုပ်ငန်းစဉ်များကို အလိုအလျောက်လုပ်ဆောင်ခြင်း၊ အလုပ်ခွဲဝေပေးခြင်းနှင့် dynamic အလုပ်စီမံခန့်ခွဲမှုအတွက် ယန္တရားများကို ပံ့ပိုးပေးသည်။

- **အကြောင်းအရာ နားလည်မှုနှင့် လိုက်လျောညီထွေဖြစ်မှု**: agent များအား အကြောင်းအရာကို နားလည်နိုင်စေခြင်း၊ ပြောင်းလဲနေသော ပတ်ဝန်းကျင်များနှင့် လိုက်လျောညီထွေဖြစ်နိုင်စေခြင်းနှင့် အချိန်နှင့်တပြေးညီ အချက်အလက်များအပေါ် အခြေခံ၍ ဆုံးဖြတ်ချက်များ ချမှတ်နိုင်စေခြင်းများဖြင့် တပ်ဆင်ပေးသည်။

ခြုံပြောရလျှင်၊ agent များသည် သင်အား ပိုမိုများပြားသော အရာများ လုပ်ဆောင်နိုင်စေပြီး အလိုအလျောက်လုပ်ဆောင်မှုကို နောက်တစ်အဆင့်သို့ တက်လှမ်းစေကာ ၎င်းတို့၏ ပတ်ဝန်းကျင်မှ လိုက်လျောညီထွေဖြစ်နိုင်ပြီး သင်ယူနိုင်သော ပိုမိုကောင်းမွန်သော စနစ်များ ဖန်တီးနိုင်စေသည်။

## Agent ၏ စွမ်းရည်များကို လျင်မြန်စွာ prototype တည်ဆောက်ခြင်း၊ ပြန်လည်ပြင်ဆင်ခြင်းနှင့် မြှင့်တင်ခြင်းများကို မည်သို့ လုပ်ဆောင်နိုင်မည်နည်း?

ယနေ့ခေတ် AI များသည် လျင်မြန်စွာ တိုးတက်နေသော်လည်း AI Agent Framework အများစုတွင် တူညီသောအရာများ အချို့ရှိပြီး ၎င်းတို့သည် modular components၊ collaborative tools နှင့် real-time learning တို့ဖြစ်သည်။ ဤအချက်များကို နက်ရှိုင်းစွာ လေ့လာကြည့်ကြပါစို့-

- **Modular Components များကို အသုံးပြုခြင်း**: AI SDK များသည် AI နှင့် Memory connector များ၊ ဘာသာစကား သို့မဟုတ် code plugin များကို အသုံးပြု၍ function calling၊ prompt template များနှင့် အခြားအရာများကဲ့သို့သော ကြိုတင်တည်ဆောက်ထားသော အစိတ်အပိုင်းများကို ပေးအပ်သည်။

- **Collaborative Tools များကို အသုံးချခြင်း**: သီးခြား အခန်းကဏ္ဍများနှင့် အလုပ်များဖြင့် agent များကို ဒီဇိုင်းပြုလုပ်ခြင်းသည် ပူးပေါင်းဆောင်ရွက်သော လုပ်ငန်းစဉ်များကို ပိုမိုကောင်းမွန်အောင် လုပ်ဆောင်စေနိုင်သည်။

- **အချိန်နှင့်တပြေးညီ သင်ယူခြင်း**: agent များသည် အပြန်အလှန်ဆက်သွယ်မှုများမှ သင်ယူပြီး ၎င်းတို့၏ အပြုအမူကို dynamic ပြောင်းလဲနိုင်သော feedback loop များကို အကောင်အထည်ဖော်ခြင်း။

### Modular Components များကို အသုံးပြုခြင်း

Microsoft Semantic Kernel နှင့် LangChain ကဲ့သို့သော SDK များသည် AI connector များ၊ prompt template များနှင့် memory management များကဲ့သို့သော ကြိုတင်တည်ဆောက်ထားသော အစိတ်အပိုင်းများကို ပေးအပ်သည်။

**ထိုအရာများကို အဖွဲ့အစည်းများက မည်သို့ အသုံးပြုနိုင်သနည်း**: အဖွဲ့များသည် ဤအစိတ်အပိုင်းများကို လျင်မြန်စွာ ပေါင်းစပ်၍ အစမှ စတင်ခြင်းမပြုဘဲ လုပ်ဆောင်နိုင်သော prototype တစ်ခု ဖန်တီးနိုင်ကြပြီး လျင်မြန်သော စမ်းသပ်မှုနှင့် ပြန်လည်ပြင်ဆင်မှုကို ခွင့်ပြုပေးသည်။

**လက်တွေ့တွင် မည်သို့ လုပ်ဆောင်သနည်း**: သင်သည် အသုံးပြုသူ၏ input မှ အချက်အလက်ကို ထုတ်ယူရန် ကြိုတင်တည်ဆောက်ထားသော parser တစ်ခု၊ ဒေတာသိမ်းဆည်းခြင်းနှင့် ပြန်လည်ရယူခြင်းအတွက် memory module တစ်ခုနှင့် အသုံးပြုသူများနှင့် အပြန်အလှန်ဆက်သွယ်ရန် prompt generator တစ်ခုတို့ကို အသုံးပြုနိုင်သည်၊ ဤအစိတ်အပိုင်းများကို အစမှ တည်ဆောက်ရန် မလိုအပ်တော့ပေ။

**ဥပမာ ကုဒ်များ**။ Model သည် အသုံးပြုသူ၏ input ကို တုံ့ပြန်ရန် auto-function calling ကို အသုံးပြုသော Semantic Kernel Python နှင့် .Net နှင့်အတူ ကြိုတင်တည်ဆောက်ထားသော AI Connector ကို မည်သို့ အသုံးပြုနိုင်သည်ကို ဥပမာများကို လေ့လာကြည့်ကြပါစို့-

``` python
# Semantic Kernel Python Example

import asyncio
from typing import Annotated

from semantic_kernel.connectors.ai import FunctionChoiceBehavior
from semantic_kernel.connectors.ai.open_ai import AzureChatCompletion, AzureChatPromptExecutionSettings
from semantic_kernel.contents import ChatHistory
from semantic_kernel.functions import kernel_function
from semantic_kernel.kernel import Kernel

# Define a ChatHistory object to hold the conversation's context
chat_history = ChatHistory()
chat_history.add_user_message("I'd like to go to New York on January 1, 2025")


# Define a sample plugin that contains the function to book travel
class BookTravelPlugin:
    """A Sample Book Travel Plugin"""

    @kernel_function(name="book_flight", description="Book travel given location and date")
    async def book_flight(
        self, date: Annotated[str, "The date of travel"], location: Annotated[str, "The location to travel to"]
    ) -> str:
        return f"Travel was booked to {location} on {date}"

# Create the Kernel
kernel = Kernel()

# Add the sample plugin to the Kernel object
kernel.add_plugin(BookTravelPlugin(), plugin_name="book_travel")

# Define the Azure OpenAI AI Connector
chat_service = AzureChatCompletion(
    deployment_name="YOUR_DEPLOYMENT_NAME", 
    api_key="YOUR_API_KEY", 
    endpoint="https://<your-resource>.azure.openai.com/",
)

# Define the request settings to configure the model with auto-function calling
request_settings = AzureChatPromptExecutionSettings(function_choice_behavior=FunctionChoiceBehavior.Auto())


async def main():
    # Make the request to the model for the given chat history and request settings
    # The Kernel contains the sample that the model will request to invoke
    response = await chat_service.get_chat_message_content(
        chat_history=chat_history, settings=request_settings, kernel=kernel
    )
    assert response is not None

    """
    Note: In the auto function calling process, the model determines it can invoke the 
    `BookTravelPlugin` using the `book_flight` function, supplying the necessary arguments. 
    
    For example:

    "tool_calls": [
        {
            "id": "call_abc123",
            "type": "function",
            "function": {
                "name": "BookTravelPlugin-book_flight",
                "arguments": "{'location': 'New York', 'date': '2025-01-01'}"
            }
        }
    ]

    Since the location and date arguments are required (as defined by the kernel function), if the 
    model lacks either, it will prompt the user to provide them. For instance:

    User: Book me a flight to New York.
    Model: Sure, I'd love to help you book a flight. Could you please specify the date?
    User: I want to travel on January 1, 2025.
    Model: Your flight to New York on January 1, 2025, has been successfully booked. Safe travels!
    """

    print(f"`{response}`")
    # Example AI Model Response: `Your flight to New York on January 1, 2025, has been successfully booked. Safe travels! ✈️🗽`

    # Add the model's response to our chat history context
    chat_history.add_assistant_message(response.content)


if __name__ == "__main__":
    asyncio.run(main())
```
```csharp
// Semantic Kernel C# example

using Microsoft.SemanticKernel;
using Microsoft.SemanticKernel.ChatCompletion;
using System.ComponentModel;
using Microsoft.SemanticKernel.Connectors.AzureOpenAI;

ChatHistory chatHistory = [];
chatHistory.AddUserMessage("I'd like to go to New York on January 1, 2025");

var kernelBuilder = Kernel.CreateBuilder();
kernelBuilder.AddAzureOpenAIChatCompletion(
    deploymentName: "NAME_OF_YOUR_DEPLOYMENT",
    apiKey: "YOUR_API_KEY",
    endpoint: "YOUR_AZURE_ENDPOINT"
);
kernelBuilder.Plugins.AddFromType<BookTravelPlugin>("BookTravel"); 
var kernel = kernelBuilder.Build();

var settings = new AzureOpenAIPromptExecutionSettings()
{
    FunctionChoiceBehavior = FunctionChoiceBehavior.Auto()
};

var chatCompletion = kernel.GetRequiredService<IChatCompletionService>();

var response = await chatCompletion.GetChatMessageContentAsync(chatHistory, settings, kernel);

/*
Behind the scenes, the model recognizes the tool to call, what arguments it already has (location) and (date)
{

"tool_calls": [
    {
        "id": "call_abc123",
        "type": "function",
        "function": {
            "name": "BookTravelPlugin-book_flight",
            "arguments": "{'location': 'New York', 'date': '2025-01-01'}"
        }
    }
]
*/

Console.WriteLine(response.Content);
chatHistory.AddMessage(response!.Role, response!.Content!);

// Example AI Model Response: Your flight to New York on January 1, 2025, has been successfully booked. Safe travels! ✈️🗽

// Define a plugin that contains the function to book travel
public class BookTravelPlugin
{
    [KernelFunction("book_flight")]
    [Description("Book travel given location and date")]
    public async Task<string> BookFlight(DateTime date, string location)
    {
        return await Task.FromResult( $"Travel was booked to {location} on {date}");
    }
}
```

ဤဥပမာမှ သင်တွေ့ရှိနိုင်သည်မှာ အသုံးပြုသူ၏ input မှ အဓိက အချက်အလက်များကို ထုတ်ယူရန် ကြိုတင်တည်ဆောက်ထားသော parser ကို မည်သို့ အသုံးချနိုင်သည်ကို ဖြစ်သည်၊ ဥပမာအားဖြင့် လေယာဉ်ပျံ ကြိုတင်မှာကြားမှု တောင်းဆိုချက်တွင်ပါရှိသော မူလနေရာ၊ ခရီးဆုံးရာနေရာနှင့် ရက်စွဲများကို ထုတ်ယူခြင်းပင်ဖြစ်သည်။ ဤ modular ချဉ်းကပ်နည်းသည် သင်အား အဆင့်မြင့် logic များအပေါ် အာရုံစိုက်နိုင်စေပါသည်။

## Collaborative Tools များကို အသုံးချခြင်း
CrewAI၊ Microsoft AutoGen နှင့် Semantic Kernel ကဲ့သို့သော Framework များသည် အတူတကွ လုပ်ဆောင်နိုင်သော မျိုးစုံ agent များ ဖန်တီးခြင်းကို လွယ်ကူစေပါသည်။

အဖွဲ့များ မည်သို့ အသုံးပြုနိုင်သနည်း - အဖွဲ့များသည် သီးခြား အခန်းကဏ္ဍများနှင့် အလုပ်များဖြင့် agent များကို ဒီဇိုင်းပြုလုပ်နိုင်ကြပြီး ပူးပေါင်းဆောင်ရွက်သော လုပ်ငန်းစဉ်များကို စမ်းသပ်ခြင်းနှင့် သန့်စင်ခြင်းများ ပြုလုပ်ကာ စနစ်၏ ခြုံငုံထိရောက်မှုကို မြှင့်တင်နိုင်ကြသည်။

လက်တွေ့တွင် မည်သို့ လုပ်ဆောင်သနည်း - သင်သည် agent များ၏ အဖွဲ့တစ်ဖွဲ့ကို ဖန်တီးနိုင်ပြီး agent တစ်ခုစီတွင် ဒေတာရယူခြင်း၊ ခွဲခြမ်းစိတ်ဖြာခြင်း သို့မဟုတ် ဆုံးဖြတ်ချက်ချမှတ်ခြင်းကဲ့သို့သော အထူးပြု လုပ်ဆောင်ချက်များ ရှိသည်။ ဤ agent များသည် အသုံးပြုသူ၏ မေးခွန်းကို ဖြေဆိုခြင်း သို့မဟုတ် အလုပ်တစ်ခုကို ပြီးစီးအောင်လုပ်ခြင်းကဲ့သို့သော ဘုံရည်မှန်းချက်ကို အောင်မြင်ရရှိရန် ဆက်သွယ်ပြီး အချက်အလက်များကို မျှဝေနိုင်ကြသည်။

ဥပမာ ကုဒ် (AutoGen):
python# creating agents, then create a round robin schedule where they can work together, in this case in order
# Data Retrieval Agent
# Data Analysis Agent
# Decision Making Agent
agent_retrieve = AssistantAgent(
    name="dataretrieval",
    model_client=model_client,
    tools=[retrieve_tool],
    system_message="Use tools to solve tasks."
)
agent_analyze = AssistantAgent(
    name="dataanalysis",
    model_client=model_client,
    tools=[analyze_tool],
    system_message="Use tools to solve tasks."
)
# conversation ends when user says "APPROVE"
termination = TextMentionTermination("APPROVE")
user_proxy = UserProxyAgent("user_proxy", input_func=input)
team = RoundRobinGroupChat([agent_retrieve, agent_analyze, user_proxy], termination_condition=termination)
stream = team.run_stream(task="Analyze data", max_turns=10)
# Use asyncio.run(...) when running in a script.
await Console(stream)
ယခင် ကုဒ်တွင် သင်တွေ့ရှိနိုင်သည်မှာ ဒေတာကို ခွဲခြမ်းစိတ်ဖြာရန် မျိုးစုံ agent များ အတူတကွ လုပ်ဆောင်ရသော task တစ်ခုကို မည်သို့ ဖန်တီးနိုင်သည်ကို ဖြစ်သည်။ Agent တစ်ခုစီသည် သီးခြား လုပ်ဆောင်ချက်တစ်ခုကို ဆောင်ရွက်ပြီး လိုချင်သော ရလဒ်ကို အောင်မြင်ရရှိရန် agent များကို ညှိနှိုင်းခြင်းဖြင့် task ကို လုပ်ဆောင်သည်။ အထူးပြု အခန်းကဏ္ဍများရှိသော သီးခြား agent များ ဖန်တီးခြင်းဖြင့် သင်သည် task ထိရောက်မှုနှင့် စွမ်းဆောင်ရည်ကို မြှင့်တင်နိုင်သည်။
အချိန်နှင့်တပြေးညီ သင်ယူခြင်း
အဆင့်မြင့် framework များသည် အချိน်နှင့်တပြေးညီ အကြောင်းအရာ နားလည်မှုနှင့် လိုက်လျောညီထွေဖြစ်မှုအတွက် စွမ်းရည်များကို ပံ့ပိုးပေးပါသည်။
အဖွဲ့များ မည်သို့ အသုံးပြုနိုင်သနည်း: အဖွဲ့များသည် agent များသည် အပြန်အလှန်ဆက်သွယ်မှုများမှ သင်ယူပြီး ၎င်းတို့၏ အပြုအမူကို dynamic ပြောင်းလဲနိုင်သော feedback loop များကို အကောင်အထည်ဖော်နိုင်ကြပြီး ၎င်းသည် စွမ်းရည်များ၏ ဆက်တိုက် တိုးတက်မှုနှင့် သန့်စင်မှုကို ဖြစ်စေသည်။
လက်တွေ့တွင် မည်သို့ လုပ်ဆောင်သနည်း: Agent များသည် အသုံးပြုသူ၏ အကြံပြုချက်များ၊ ပတ်ဝန်းကျင်ဆိုင်ရာ ဒေတာများနှင့် task ရလဒ်များကို ခွဲခြမ်းစိတ်ဖြာ၍ ၎င်းတို့၏ အသိပညာ base ကို update လုပ်ခြင်း၊ ဆုံးဖြတ်ချက်ချမှတ်သော algorithm များကို ချိန်ညှိခြင်းနှင့် အချိန်ကြာလာသည်နှင့်အမျှ စွမ်းဆောင်ရည်ကို မြှင့်တင်ခြင်းများ ပြုလုပ်နိုင်သည်။ ဤ ထပ်တလဲလဲ သင်ယူမှု လုပ်ငန်းစဉ်သည် agent များအား ပြောင်းလဲနေသော အခြေအနေများနှင့် အသုံးပြုသူ၏ နှစ်သက်မှုများနှင့် လိုက်လျောညီထွေဖြစ်နိုင်စေပြီး ခြုံငုံ စနစ်ထိရောက်မှုကို မြှင့်တင်ပေးသည်။
AutoGen၊ Semantic Kernel နှင့် Azure AI Agent Service တို့အကြား ကွာခြားချက်များမှာ မည်သည့်အရာများနည်း?
ဤ framework များကို နှိုင်းယှဉ်ရန် နည်းလမ်းများစွာ ရှိသော်လည်း ၎င်းတို့၏ ဒီဇိုင်း၊ စွမ်းရည်များနှင့် ပစ်မှတ် အသုံးပြုမှု ကိစ္စရပ်များအပေါ် အခြေခံ၍ အဓိက ကွာခြားချက်အချို့ကို လေ့လာကြည့်ကြပါစို့-

Semantic Kernel Python ကို အသုံးပြု၍၊ အသုံးပြုသူမှ သတ်မှတ်ထားသော plugin နှင့် Azure AI Agent တစ်ခုကို ဖန်တီးနိုင်သည်:

```python
import asyncio
from typing import Annotated

from azure.identity.aio import DefaultAzureCredential

from semantic_kernel.agents import AzureAIAgent, AzureAIAgentSettings, AzureAIAgentThread
from semantic_kernel.contents import ChatMessageContent
from semantic_kernel.contents import AuthorRole
from semantic_kernel.functions import kernel_function


# Define a sample plugin for the sample
class MenuPlugin:
    """A sample Menu Plugin used for the concept sample."""

    @kernel_function(description="Provides a list of specials from the menu.")
    def get_specials(self) -> Annotated[str, "Returns the specials from the menu."]:
        return """
        Special Soup: Clam Chowder
        Special Salad: Cobb Salad
        Special Drink: Chai Tea
        """

    @kernel_function(description="Provides the price of the requested menu item.")
    def get_item_price(
        self, menu_item: Annotated[str, "The name of the menu item."]
    ) -> Annotated[str, "Returns the price of the menu item."]:
        return "$9.99"


async def main() -> None:
    ai_agent_settings = AzureAIAgentSettings.create()

    async with (
        DefaultAzureCredential() as creds,
        AzureAIAgent.create_client(
            credential=creds,
            conn_str=ai_agent_settings.project_connection_string.get_secret_value(),
        ) as client,
    ):
        # Create agent definition
        agent_definition = await client.agents.create_agent(
            model=ai_agent_settings.model_deployment_name,
            name="Host",
            instructions="Answer questions about the menu.",
        )

        # Create the AzureAI Agent using the defined client and agent definition
        agent = AzureAIAgent(
            client=client,
            definition=agent_definition,
            plugins=[MenuPlugin()],
        )

        # Create a thread to hold the conversation
        # If no thread is provided, a new thread will be
        # created and returned with the initial response
        thread: AzureAIAgentThread | None = None

        user_inputs = [
            "Hello",
            "What is the special soup?",
            "How much does that cost?",
            "Thank you",
        ]

        try:
            for user_input in user_inputs:
                print(f"# User: '{user_input}'")
                # Invoke the agent for the specified thread
                response = await agent.get_response(
                    messages=user_input,
                    thread_id=thread,
                )
                print(f"# {response.name}: {response.content}")
                thread = response.thread
        finally:
            await thread.delete() if thread else None
            await client.agents.delete_agent(agent.id)


if __name__ == "__main__":
    asyncio.run(main())
```

### အဓိက အယူအဆများ

Azure AI Agent Service တွင် အောက်ပါ အဓိက အယူအဆများ ရှိသည်:

- **Agent**။ Azure AI Agent Service သည် Azure AI Foundry နှင့် ပေါင်းစပ်ထားသည်။ AI Foundry အတွင်းတွင်၊ AI Agent တစ်ခုသည် မေးခွန်းများကို ဖြေဆိုရန် (RAG)၊ လုပ်ဆောင်ချက်များ ဆောင်ရွက်ရန်၊ သို့မဟုတ် workflows များကို လုံးဝ အလိုအလျောက် လုပ်ဆောင်ရန် အသုံးပြုနိုင်သော "စမတ်" microservice တစ်ခုအဖြစ် ဆောင်ရွက်သည်။ ၎င်းသည် generative AI models များ၏ စွမ်းအားကို အစစ်အမှန် ဒေတာ အရင်းအမြစ်များကို ရယူနိုင်ပြီး အပြန်အလှန် ဆက်သွယ်နိုင်စေသော tools များနှင့် ပေါင်းစပ်ခြင်းဖြင့် ရရှိသည်। Agent တစ်ခု၏ ဥပမာ ဖြစ်သည်:

    ```python
    agent = project_client.agents.create_agent(
        model="gpt-4o-mini",
        name="my-agent",
        instructions="You are helpful agent",
        tools=code_interpreter.definitions,
        tool_resources=code_interpreter.resources,
    )
    ```

    ဤ ဥပမာတွင်၊ agent တစ်ခုကို model `gpt-4o-mini`၊ နာမည် `my-agent`၊ နှင့် ညွှန်ကြားချက် `You are helpful agent` တို့ဖြင့် ဖန်တီးထားသည်။ Agent သည် code interpretation လုပ်ငန်းများ ဆောင်ရွက်ရန် tools နှင့် resources များဖြင့် တပ်ဆင်ထားသည်။

- **Thread နှင့် messages**။ Thread သည် အခြား အရေးကြီးသော အယူအဆတစ်ခု ဖြစ်သည်။ ၎င်းသည် agent နှင့် အသုံးပြုသူကြား စကားဝိုင်း သို့မဟုတ် အပြန်အလှန် ဆက်သွယ်မှုကို ကိုယ်စားပြုသည်။ Threads များကို စကားဝိုင်း၏ တိုးတက်မှုကို ခြေရာခံရန်၊ context သတင်းအချက်အလက်များ သိမ်းဆည်းရန်၊ နှင့် အပြန်အလှန် ဆက်သွယ်မှု၏ အခြေအနေကို စီမံခန့်ခွဲရန် အသုံးပြုနိုင်သည်။ Thread တစ်ခု၏ ဥပမာ ဖြစ်သည်:

    ```python
    thread = project_client.agents.create_thread()
    message = project_client.agents.create_message(
        thread_id=thread.id,
        role="user",
        content="Could you please create a bar chart for the operating profit using the following data and provide the file to me? Company A: $1.2 million, Company B: $2.5 million, Company C: $3.0 million, Company D: $1.8 million",
    )
    
    # Ask the agent to perform work on the thread
    run = project_client.agents.create_and_process_run(thread_id=thread.id, agent_id=agent.id)
    
    # Fetch and log all messages to see the agent's response
    messages = project_client.agents.list_messages(thread_id=thread.id)
    print(f"Messages: {messages}")
    ```

    ယခင် ကုဒ်တွင်၊ thread တစ်ခုကို ဖန်တီးသည်။ ထို့နောက်၊ thread ထံ message တစ်ခု ပို့သည်။ `create_and_process_run` ကို ခေါ်ခြင်းဖြင့်၊ agent ကို thread တွင် လုပ်ဆောင်ရန် တောင်းဆိုသည်။ နောက်ဆုံးတွင်၊ agent ၏ တုံ့ပြန်မှုကို မြင်ရန် messages များကို ရယူပြီး မှတ်တမ်းတင်သည်။ Messages များသည် အသုံးပြုသူ နှင့် agent ကြား စကားဝိုင်း၏ တိုးတက်မှုကို ညွှန်ပြသည်။ Messages များသည် စာသား၊ ရုပ်ပုံ၊ သို့မဟုတ် ဖိုင်ကဲ့သို့သော အမျိုးအစား အမျိုးမျိုး ဖြစ်နိုင်သည်ကို နားလည်ရန် အရေးကြီးသည်၊ ဆိုလိုသည်မှာ agents ၏ လုပ်ဆောင်မှုသည် ဥပမာအားဖြင့် ရုပ်ပုံ သို့မဟုတ် စာသား တုံ့ပြန်မှု ရရှိစေသည်။ ဖွံ့ဖြိုးတိုးတက်သူအနေဖြင့်၊ သင်သည် ဤ သတင်းအချက်အလက်ကို ထပ်မံ လုပ်ဆောင်ရန် သို့မဟုတ် အသုံးပြုသူထံ တင်ပြရန် အသုံးပြုနိုင်သည်။

- **အခြား AI frameworks များနှင့် ပေါင်းစပ်မှု**။ Azure AI Agent service သည် AutoGen နှင့် Semantic Kernel ကဲ့သို့သော အခြား frameworks များနှင့် အပြန်အလှန် ဆက်သွယ်နိုင်ပြီး၊ ဆိုလိုသည်မှာ သင်သည် သင်၏ app ၏ အစိတ်အပိုင်းတစ်ခုကို ဤ frameworks များထဲမှ တစ်ခုတွင် တည်ဆောက်နိုင်ပြီး ဥပမာအားဖြင့် Agent service ကို orchestrator အဖြစ် အသုံးပြုနိုင်သည် သို့မဟုတ် Agent service တွင် အရာအားလုံးကို တည်ဆောက်နိုင်သည်။

**အသုံးပြုမှုများ**: Azure AI Agent Service သည် လုံခြုံသော၊ scalable၊ နှင့် ပြောင်းလွယ်ပြင်လွယ် AI agent အသုံးချမှု လိုအပ်သော enterprise applications များအတွက် ဒီဇိုင်းထုတ်ထားသည်။

## ဤ frameworks များကြား ကွာခြားချက်မှာ ဘာလဲ?
 
ဤ frameworks များကြားတွင် overlap များစွာ ရှိနေသည်ဟု ထင်ရသော်လည်း၊ ၎င်းတို့၏ ဒီဇိုင်း၊ စွမ်းရည်များ၊ နှင့် ပစ်မှတ် အသုံးပြုမှုများတွင် အဓိက ကွာခြားချက်များ ရှိသည်:
 
- **AutoGen**: Multi-agent systems များအကြောင်း ခေါင်းဆောင်သော သုတေသနကို အဓိကထား၍ စမ်းသပ်မှု framework တစ်ခုဖြစ်သည်။ ၎င်းသည် ရှုပ်ထွေးသော multi-agent systems များကို စမ်းသပ်ပြီး prototype ပြုလုပ်ရန် အကောင်းဆုံး နေရာဖြစ်သည်။
- **Semantic Kernel**: Enterprise agentic applications များကို တည်ဆောက်ရန်အတွက် production-ready agent library တစ်ခုဖြစ်သည်။ Event-driven, distributed agentic applications များကို အဓိကထားပြီး၊ multiple LLMs နှင့် SLMs များ၊ tools များ၊ နှင့် single/multi-agent design patterns များကို အသုံးပြုနိုင်စေသည်။
- **Azure AI Agent Service**: Agents များအတွက် Azure Foundry တွင် platform နှင့် deployment service တစ်ခုဖြစ်သည်။ ၎င်းသည် Azure OpenAI၊ Azure AI Search၊ Bing Search နှင့် code execution ကဲ့သို့သော Azure Found မှ ပံ့ပိုးထားသော services များနှင့် connectivity တည်ဆောက်မှုကို ပေးဆောင်သည်။
 
မည်သည့်တစ်ခုကို ရွေးချယ်ရမည်ကို မသေချာသေးလား?

### အသုံးပြုမှုများ
 
သင့်အား အဖြေရရှိရန် အဖြစ်များသော အသုံးပြုမှုများကို လေ့လာခြင်းဖြင့် ကူညီနိုင်မလား ကြည့်ကြပါစို့:
 
> မေးခွန်း: ကျွန်ုပ်သည် စမ်းသပ်ခြင်း၊ သင်ယူခြင်း နှင့် proof-of-concept agent applications များ တည်ဆောက်ခြင်းကို လုပ်နေပြီး၊ လျင်မြန်စွာ တည်ဆောက်ပြီး စမ်းသပ်နိုင်စေလိုသည်။
>

>အဖြေ: AutoGen သည် ဤ scenario အတွက် ကောင်းမွန်သော ရွေးချယ်မှုတစ်ခု ဖြစ်လိမ့်မည်၊ အကြောင်းမှာ ၎င်းသည် event-driven, distributed agentic applications များကို အဓိကထားပြီး အဆင့်မြင့် multi-agent design patterns များကို ပံ့ပိုးသည်။

> မေးခွန်း: ဤ အသုံးပြုမှုအတွက် AutoGen ကို Semantic Kernel နှင့် Azure AI Agent Service ထက် ပိုကောင်းစေသည့် အရာများမှာ ဘာလဲ?
>
> အဖြေ: AutoGen သည် event-driven, distributed agentic applications များအတွက် အထူးသတ်မှတ်ထားပြီး၊ ကုဒ်ထုတ်လုပ်မှု နှင့် ဒေတာခွဲခြမ်းစိတ်ဖြာမှု လုပ်ငန်းများကို အလိုအလျောက်လုပ်ဆောင်ရန် သင့်လျော်စေသည်။ ၎င်းသည် ရှုပ်ထွေးသော multi-agent systems များကို ထိရောက်စွာ တည်ဆောက်ရန် လိုအပ်သော tools များ နှင့် စွမ်းရည်များကို ပေးဆောင်သည်။

>မေးခွန်း: Azure AI Agent Service သည် ဤနေရာတွင်လည်း လုပ်ဆောင်နိုင်သည်ဟု ထင်ရသည်၊ ၎င်းတွင် ကုဒ်ထုတ်လုပ်မှု နှင့် အခြားများအတွက် tools များ ရှိသလား?

>
> အဖြေ: ဟုတ်ကဲ့၊ Azure AI Agent Service သည် agents များအတွက် platform service တစ်ခုဖြစ်ပြီး multiple models၊ Azure AI Search၊ Bing Search နှင့် Azure Functions များအတွက် တည်ဆောက်ထားသော လုပ်ဆောင်နိုင်မှုများကို ထည့်သွင်းပေးသည်။ ၎င်းသည် Foundry Portal တွင် သင်၏ agents များကို တည်ဆောက်ပြီး စကေးအကြီးတွင် အသုံးချရန် လွယ်ကူစေသည်။
 
> မေးခွန်း: ကျွန်ုပ် ရှုပ်ထွေးနေသေးသည်၊ ရွေးချယ်မှုတစ်ခုပဲ ပေးပါ
>
> အဖြေ: အကောင်းဆုံး ရွေးချယ်မှုမှာ သင်၏ application ကို Semantic Kernel တွင် ဦးစွာ တည်ဆောက်ပြီး ထို့နောက် သင်၏ agent ကို အသုံးချရန် Azure AI Agent Service ကို အသုံးပြုခြင်း ဖြစ်သည်။ ဤ approach သည် Semantic Kernel တွင် multi-agent systems များ တည်ဆောက်ရန် စွမ်းအားကို အသုံးချ၍ သင်၏ agents များကို လွယ်ကူစွာ ထိန်းသိမ်းစေသည်။ ထို့အပြင်၊ Semantic Kernel တွင် AutoGen တွင် connector တစ်ခု ရှိပြီး နှစ် frameworks အတူတကွ အသုံးပြုရန် လွယ်ကူစေသည်။
 
အဓိက ကွာခြားချက်များကို ဇယားတစ်ခုတွင် အကျဉ်းချုပ်ကြည့်ကြပါစို့:

| Framework | အဓိကတည်ရာ | အဓိက အယူအဆများ | အသုံးပြုမှုများ |
| --- | --- | --- | --- |
| AutoGen | Event-driven, distributed agentic applications | Agents, Personas, Functions, Data | ကုဒ်ထုတ်လုပ်မှု၊ ဒေတာခွဲခြမ်းစိတ်ဖြာမှု လုပ်ငန်းများ |
| Semantic Kernel | လူသားကဲ့သို့ စာသားအကြောင်းအရာ နားလည်ခြင်း နှင့် ထုတ်လုပ်ခြင်း | Agents, Modular Components, Collaboration | သဘာဝဘာသာစကား နားလည်မှု၊ အကြောင်းအရာ ထုတ်လုပ်မှု |
| Azure AI Agent Service | ပြောင်းလွယ်ပြင်လွယ် models များ၊ enterprise လုံခြုံရေး၊ ကုဒ်ထုတ်လုပ်မှု၊ Tool calling | Modularity, Collaboration, Process Orchestration | လုံခြုံသော၊ scalable၊ နှင့် ပြောင်းလွယ်ပြင်လွယ် AI agent အသုံးချမှု |

ဤ frameworks များ တစ်ခုချင်းစီအတွက် စံပြ အသုံးပြုမှုမှာ ဘာလဲ?

## ကျွန်ုပ်၏ လက်ရှိ Azure ecosystem tools များကို တိုက်ရိုက် ပေါင်းစပ်နိုင်သလား၊ သို့မဟုတ် standalone solutions များ လိုအပ်သလား?

အဖြေမှာ ဟုတ်ကဲ့၊ သင်သည် သင်၏ လက်ရှိ Azure ecosystem tools များကို Azure AI Agent Service နှင့် အထူးသဖြင့် တိုက်ရိုက် ပေါင်းစပ်နိုင်သည်၊ အကြောင်းမှာ ၎င်းသည် အခြား Azure services များနှင့် လွတ်လပ်စွာ လုပ်ဆောင်ရန် တည်ဆောက်ထားသည်။ သင်သည် ဥပမာအားဖြင့် Bing၊ Azure AI Search၊ နှင့် Azure Functions တို့ကို ပေါင်းစပ်နိုင်သည်။ Azure AI Foundry နှင့်လည်း နက်ရှိုင်းသော ပေါင်းစပ်မှု ရှိသည်။

AutoGen နှင့် Semantic Kernel အတွက်လည်း သင်သည် Azure services များနှင့် ပေါင်းစပ်နိုင်သော်လည်း၊ သင်၏ ကုဒ်မှ Azure services များကို ခေါ်ရန် လိုအပ်နိုင်သည်။ ပေါင်းစပ်ရန် အခြား နည်းလမ်းမှာ သင်၏ agents များမှ Azure services များနှင့် အပြန်အလှန် ဆက်သွယ်ရန် Azure SDKs များကို အသုံးပြုခြင်း ဖြစ်သည်။ ထို့အပြင်၊ ဖော်ပြခဲ့သည့်အတိုင်း၊ သင်သည် AutoGen သို့မဟုတ် Semantic Kernel တွင် တည်ဆောက်ထားသော သင်၏ agents များအတွက် Azure AI Agent Service ကို orchestrator အဖြစ် အသုံးပြုနိုင်ပြီး ၎င်းသည် Azure ecosystem သို့ လွယ်ကူသော ရယူမှုကို ပေးလိမ့်မည်။

## ကိုးကားချက်များ

- <a href="https://techcommunity.microsoft.com/blog/azure-ai-services-blog/introducing-azure-ai-agent-service/4298357" target="_blank">Azure Agent Service</a>
- <a href="https://devblogs.microsoft.com/semantic-kernel/microsofts-agentic-ai-frameworks-autogen-and-semantic-kernel/" target="_blank">Semantic Kernel and AutoGen</a>
- <a href="https://learn.microsoft.com/semantic-kernel/frameworks/agent/?pivots=programming-language-python" target="_blank">Semantic Kernel Python Agent Framework</a>
- <a href="https://learn.microsoft.com/semantic-kernel/frameworks/agent/?pivots=programming-language-csharp" target="_blank">Semantic Kernel .Net Agent Framework</a>
- <a href="https://learn.microsoft.com/azure/ai-services/agents/overview" target="_blank">Azure AI Agent service</a>
- <a href="https://techcommunity.microsoft.com/blog/educatordeveloperblog/using-azure-ai-agent-service-with-autogen--semantic-kernel-to-build-a-multi-agen/4363121" target="_blank">Azure AI Agent Service နှင့် AutoGen / Semantic Kernel ကို အသုံးပြု၍ multi-agent's solution တည်ဆောက်ခြင်း</a>

## ယခင် သင်ခန်းစာ

[AI Agents များနှင့် Agent အသုံးပြုမှုများ မိတ်ဆက်](../01-intro-to-ai-agents/README.md)

## နောက် သင်ခန်းစာ

[Agentic Design Patterns နားလည်ခြင်း](../03-agentic-design-patterns/README.md)
