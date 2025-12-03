# Reference
## Customer
<details><summary><code>client.customer.<a href="/src/api/resources/customer/client/Client.ts">getAllCustomers</a>({ ...params }) -> FlaqzApp.GetAllCustomersResponse</code></summary>
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

**request:** `FlaqzApp.GetAllCustomersRequest` 
    
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
            ppInfo: "Under financial history analisys"
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

## Assistant
<details><summary><code>client.assistant.<a href="/src/api/resources/assistant/client/Client.ts">getAssistants</a>({ ...params }) -> FlaqzApp.GetAssistantsResponse</code></summary>
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

**request:** `FlaqzApp.GetAssistantsRequest` 
    
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
