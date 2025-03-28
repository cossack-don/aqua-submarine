Standart names

prefix - state for states
const stateName = reactive/ref

prefix - action fro actions
const actionUpdateState = (payload) => Object.assign(stateName,payload)


1. SliceTypesName
2. SliceInitialStatesName
3. SliceApiName
4. SliceAdapterName
5. SliceMiddlewareName
6. SliceControllerName or SliceStoreControllerName
7. SliceViewName


1. SliceViewModuleName - (SliceTypesName + SliceInitialStatesName + SliceControllerName) + (SliceTypesName + SliceInitialStatesName + SliceControllerName) = SliceControllerModuleName
2. SliceControllerModuleName

Other
- SliceProviderName
- SliceFacade
- SliceAbstraction
- SliceFactory
