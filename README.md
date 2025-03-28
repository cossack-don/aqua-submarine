Standart names

prefix - state for states
const stateName = reactive/ref

prefix - action fro actions
const actionUpdateState = (payload) => Object.assign(stateName,payload)


1. SliceTypesName
2. SliceInitialStatesName
3. SliceAdapterName
4. SliceMiddlewareName
5. SliceControllerName or SliceStoreControllerName
6. SliceViewName


1. SliceViewModuleName - (SliceTypesName + SliceInitialStatesName + SliceControllerName) + (SliceTypesName + SliceInitialStatesName + SliceControllerName) = SliceControllerModuleName
2. SliceControllerModuleName

Other
- SliceProviderName
- SliceFacade
- SliceAbstraction
- SliceFactory
