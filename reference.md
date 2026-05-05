# Reference
## Customer
<details><summary><code>client.customer.<a href="/src/api/resources/customer/client/Client.ts">getAllCustomers</a>() -> FlaqzApp.GetAllCustomersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.getAllCustomers();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CustomerClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.<a href="/src/api/resources/customer/client/Client.ts">createManyCustomers</a>({ ...params }) -> FlaqzApp.CreateManyCustomersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.createManyCustomers({
    customers: [{
            email: "awesome@customer.com",
            fullName: "Awesome Customer",
            phoneNumber: "+10000000000",
            ppInfo: "Under financial history analysis"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateManyCustomersSchema` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.<a href="/src/api/resources/customer/client/Client.ts">searchCustomers</a>({ ...params }) -> FlaqzApp.SearchCustomersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.searchCustomers({
    page: 1,
    pageSize: 20,
    query: "Awesome Customer"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchCustomersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## User
<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">getUsers</a>() -> FlaqzApp.GetUsersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.getUsers();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">createUser</a>({ ...params }) -> FlaqzApp.CreateUserResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.createUser({
    email: "user@example.com",
    username: "johndoe",
    pass: "securepassword"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateUserInput` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">searchUsers</a>({ ...params }) -> FlaqzApp.SearchUsersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.searchUsers({
    page: 1,
    pageSize: 20,
    query: "johndoe"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchUsersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">deleteUser</a>({ ...params }) -> FlaqzApp.DeleteUserResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.deleteUser({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.DeleteUserRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Assistant
<details><summary><code>client.assistant.<a href="/src/api/resources/assistant/client/Client.ts">getAssistants</a>() -> FlaqzApp.GetAssistantsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.assistant.getAssistants();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AssistantClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assistant.<a href="/src/api/resources/assistant/client/Client.ts">createAssistant</a>({ ...params }) -> FlaqzApp.CreateAssistantResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.assistant.createAssistant({
    name: "My Assistant 01",
    voiceId: "5d9f0c21-2c4a-4b4d-8b8b-aad2de5542f3",
    modelId: "a4ac4276-9c26-4bb0-a563-a290f2b4c91f",
    transcriberId: "66fa9d6b-c6ac-4baf-ade4-37e16478e4b2",
    prompt: "You're a assistant that call to people and ask if they know how to make a carrot cake",
    firstMsg: "Hello!",
    firstMsgMode: "SPEAKS_FIRST",
    voiceMailMsg: "Who uses voicemail in 2077 man",
    endMsg: "Bye!",
    bgSound: "OFFICE",
    bgDenoising: true,
    structuredOutputIds: ["SALE_COMPLETED", "LEAD_STATUS"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateAssistantInput` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AssistantClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assistant.<a href="/src/api/resources/assistant/client/Client.ts">updateAssistant</a>({ ...params }) -> FlaqzApp.UpdateAssistantResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.assistant.updateAssistant({
    id: "id",
    newData: {
        name: "My Assistant 01",
        voiceId: "5d9f0c21-2c4a-4b4d-8b8b-aad2de5542f3",
        modelId: "a4ac4276-9c26-4bb0-a563-a290f2b4c91f",
        transcriberId: "66fa9d6b-c6ac-4baf-ade4-37e16478e4b2",
        prompt: "You're a assistant that call to people and ask if they know how to make a carrot cake",
        firstMsg: "Hello!",
        firstMsgMode: "SPEAKS_FIRST",
        voiceMailMsg: "Who uses voicemail in 2077 man",
        endMsg: "Bye!",
        bgSound: "OFFICE",
        bgDenoising: true,
        structuredOutputIds: ["SALE_COMPLETED", "LEAD_STATUS"]
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.UpdateAssistant` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AssistantClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assistant.<a href="/src/api/resources/assistant/client/Client.ts">searchAssistants</a>({ ...params }) -> FlaqzApp.SearchAssistantsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.assistant.searchAssistants({
    page: 1,
    pageSize: 20,
    query: "Awesome Customer"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchAssistantsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AssistantClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assistant.<a href="/src/api/resources/assistant/client/Client.ts">searchCampaigns</a>({ ...params }) -> FlaqzApp.SearchCampaignsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.assistant.searchCampaigns({
    page: 1,
    pageSize: 20,
    query: "Wow a amazing campaign"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchCampaignsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AssistantClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Model
<details><summary><code>client.model.<a href="/src/api/resources/model/client/Client.ts">getModels</a>() -> FlaqzApp.GetModelsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.model.getModels();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ModelClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.model.<a href="/src/api/resources/model/client/Client.ts">createModel</a>({ ...params }) -> FlaqzApp.CreateModelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.model.createModel({
    model: "llama-3.1-8b-instant",
    provider: "groq",
    maxTokens: 128,
    temperature: 0.6
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateModelInput` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ModelClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.model.<a href="/src/api/resources/model/client/Client.ts">searchModels</a>({ ...params }) -> FlaqzApp.SearchModelsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.model.searchModels({
    page: 1,
    pageSize: 20,
    query: "Awesome Customer"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchModelsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ModelClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Transcriber
<details><summary><code>client.transcriber.<a href="/src/api/resources/transcriber/client/Client.ts">gettranscribers</a>() -> FlaqzApp.GettranscribersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.transcriber.gettranscribers();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `TranscriberClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transcriber.<a href="/src/api/resources/transcriber/client/Client.ts">createTranscriber</a>({ ...params }) -> FlaqzApp.CreateTranscriberResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.transcriber.createTranscriber({
    model: "nova-2",
    language: "pt-BR",
    provider: "deepgram"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateTranscriberInput` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TranscriberClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transcriber.<a href="/src/api/resources/transcriber/client/Client.ts">searchTranscribers</a>({ ...params }) -> FlaqzApp.SearchTranscribersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.transcriber.searchTranscribers({
    page: 1,
    pageSize: 20,
    query: "Awesome Customer"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchTranscribersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TranscriberClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Voice
<details><summary><code>client.voice.<a href="/src/api/resources/voice/client/Client.ts">getVoices</a>() -> FlaqzApp.GetVoicesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.voice.getVoices();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `VoiceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.voice.<a href="/src/api/resources/voice/client/Client.ts">createVoice</a>({ ...params }) -> FlaqzApp.CreateVoiceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.voice.createVoice({
    provider: "11labs",
    model: "eleven_flash_v2",
    voiceId: "33B4UnXyTNbgLmdEDh5P",
    autoMode: true,
    speed: 1,
    style: 0,
    stability: 0.5,
    similarity: 0.5,
    optimize: 2
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateVoiceInput` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VoiceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.voice.<a href="/src/api/resources/voice/client/Client.ts">searchVoices</a>({ ...params }) -> FlaqzApp.SearchVoicesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.voice.searchVoices({
    page: 1,
    pageSize: 20,
    query: "Awesome Customer"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.SearchVoicesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VoiceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Campaigns
<details><summary><code>client.campaigns.<a href="/src/api/resources/campaigns/client/Client.ts">getCampaigns</a>() -> FlaqzApp.GetCampaignsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.campaigns.getCampaigns();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CampaignsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Campaign
<details><summary><code>client.campaign.<a href="/src/api/resources/campaign/client/Client.ts">createCampaign</a>({ ...params }) -> FlaqzApp.CreateCampaignResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.campaign.createCampaign({
    campaignName: "My Awesome Campaign",
    assistantId: "8df037de-a169-4e24-8b5e-637077d57f35",
    customerIds: ["8f727d7e-a169-4e24-8b5e-637077d57f35", "df727d0e-a169-4e27-8b5e-637077d57f35"],
    published: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.CreateCampaignInput` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CampaignClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.campaign.<a href="/src/api/resources/campaign/client/Client.ts">updateCampaign</a>({ ...params }) -> FlaqzApp.UpdateCampaignResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.campaign.updateCampaign({
    id: "id",
    newData: {
        campaignName: "My Awesome Campaign",
        assistantId: "8df037de-a169-4e24-8b5e-637077d57f35",
        customerIds: ["8f727d7e-a169-4e24-8b5e-637077d57f35", "df727d0e-a169-4e27-8b5e-637077d57f35"],
        published: true
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.UpdateCampaignRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CampaignClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.campaign.<a href="/src/api/resources/campaign/client/Client.ts">deleteCampaign</a>({ ...params }) -> FlaqzApp.DeleteCampaignResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.campaign.deleteCampaign({
    id: "df727d0e-a169-4e24-8b5e-637077d57f35"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.DeleteCampaignRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CampaignClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.campaign.<a href="/src/api/resources/campaign/client/Client.ts">publishCampaign</a>({ ...params }) -> FlaqzApp.PublishCampaignResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.campaign.publishCampaign({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.PublishCampaignRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CampaignClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.campaign.<a href="/src/api/resources/campaign/client/Client.ts">runCampaign</a>({ ...params }) -> FlaqzApp.RunCampaignResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.campaign.runCampaign({
    id: "df727d0e-a169-4e24-8b5e-637077d57f35"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FlaqzApp.RunCampaignRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CampaignClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>
