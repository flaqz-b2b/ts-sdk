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
            firstName: "Awesome",
            lastName: "Customer",
            phoneNumber: "+10000000000",
            obs: "Mr. Awesome like oranges",
            cpf: "00000000000",
            birthDate: "2000-01-01T00:00:00Z",
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
