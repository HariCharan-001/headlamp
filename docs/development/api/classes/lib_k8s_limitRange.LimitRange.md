---
title: "Class: LimitRange"
linkTitle: "LimitRange"
slug: "lib_k8s_limitRange.LimitRange"
---

[lib/k8s/limitRange](../modules/lib_k8s_limitRange.md).LimitRange

## Hierarchy

- `any`

  ↳ **`LimitRange`**

## Constructors

### constructor

• **new LimitRange**(`json`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | [`KubeLimitRange`](../interfaces/lib_k8s_limitRange.KubeLimitRange.md) |

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').constructor

#### Defined in

[lib/k8s/cluster.ts:301](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L301)

## Properties

### apiEndpoint

▪ `Static` **apiEndpoint**: `Object`

#### Index signature

▪ [other: `string`]: `any`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `scale?` | { `get`: (`namespace`: `string`, `name`: `string`) => `Promise`<`any`\> ; `put`: (`body`: { `metadata`: [`KubeMetadata`](../interfaces/lib_k8s_cluster.KubeMetadata.md) ; `spec`: { `replicas`: `number`  }  }) => `Promise`<`any`\>  } |
| `scale.get` | (`namespace`: `string`, `name`: `string`) => `Promise`<`any`\> |
| `scale.put` | (`body`: { `metadata`: [`KubeMetadata`](../interfaces/lib_k8s_cluster.KubeMetadata.md) ; `spec`: { `replicas`: `number`  }  }) => `Promise`<`any`\> |

#### Defined in

[lib/k8s/limitRange.tsx:31](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/limitRange.tsx#L31)

___

### className

▪ `Static` **className**: `string`

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').className

#### Defined in

[lib/k8s/cluster.ts:302](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L302)

## Accessors

### spec

• `get` **spec**(): `any`

#### Returns

`any`

#### Defined in

[lib/k8s/limitRange.tsx:33](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/limitRange.tsx#L33)

## Methods

### apiList

▸ `Static` **apiList**(`onList`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `onList` | (`arg`: `any`[]) => `void` |

#### Returns

`any`

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').apiList

#### Defined in

[lib/k8s/cluster.ts:281](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L281)

___

### getAuthorization

▸ `Static` `Optional` **getAuthorization**(`arg`, `resourceAttrs?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `arg` | `string` |
| `resourceAttrs?` | [`AuthRequestResourceAttrs`](../interfaces/lib_k8s_cluster.AuthRequestResourceAttrs.md) |

#### Returns

`any`

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').getAuthorization

#### Defined in

[lib/k8s/cluster.ts:304](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L304)

___

### getErrorMessage

▸ `Static` **getErrorMessage**(`err?`): ``null`` \| `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `err?` | ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md) |

#### Returns

``null`` \| `string`

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').getErrorMessage

#### Defined in

[lib/k8s/cluster.ts:300](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L300)

___

### useApiGet

▸ `Static` **useApiGet**(`onGet`, `name`, `namespace?`, `onError?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `onGet` | (...`args`: `any`) => `void` |
| `name` | `string` |
| `namespace?` | `string` |
| `onError?` | (`err`: [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md)) => `void` |

#### Returns

`void`

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').useApiGet

#### Defined in

[lib/k8s/cluster.ts:287](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L287)

___

### useApiList

▸ `Static` **useApiList**(`onList`, `onError?`, `opts?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `onList` | (`arg`: `any`[]) => `void` |
| `onError?` | (`err`: [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md)) => `void` |
| `opts?` | [`ApiListOptions`](../interfaces/lib_k8s_cluster.ApiListOptions.md) |

#### Returns

`any`

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').useApiList

#### Defined in

[lib/k8s/cluster.ts:282](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L282)

___

### useGet

▸ `Static` **useGet**(`name`, `namespace?`): [`any`, ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md), (`item`: `any`) => `void`, (`err`: ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md)) => `void`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `namespace?` | `string` |

#### Returns

[`any`, ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md), (`item`: `any`) => `void`, (`err`: ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md)) => `void`]

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').useGet

#### Defined in

[lib/k8s/cluster.ts:296](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L296)

___

### useList

▸ `Static` **useList**(`opts?`): [`any`[], ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md), (`items`: `any`[]) => `void`, (`err`: ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md)) => `void`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts?` | [`ApiListOptions`](../interfaces/lib_k8s_cluster.ApiListOptions.md) |

#### Returns

[`any`[], ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md), (`items`: `any`[]) => `void`, (`err`: ``null`` \| [`ApiError`](../interfaces/lib_k8s_apiProxy.ApiError.md)) => `void`]

#### Inherited from

makeKubeObject<KubeLimitRange\>('LimitRange').useList

#### Defined in

[lib/k8s/cluster.ts:293](https://github.com/headlamp-k8s/headlamp/blob/b0236780/frontend/src/lib/k8s/cluster.ts#L293)
