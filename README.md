# ultime-modal

## Installation
To install, you can the command below:

    npm i --save ultime-modal

## Example

- you can return your component and the modal like this

```
    return (
        <div className="App">
            <button onClick={() => setIsOpen(true)}>Open modal</button>
            <Modal
                myModalButtonStyle={myModalButtonStyle}
                isOpen={isOpen}
                setIsOpen={setIsOpen}
            >
                <ModalTitle />
                <ModalContent />
            </Modal>
        </div>
    );
```
- OR like this

```
    return (
        <div className="App">
            <button onClick={() => setIsOpen(true)}>Open modal</button>
            <Modal
                myModalButtonStyle={myModalButtonStyle}
                isOpen={isOpen}
                setIsOpen={setIsOpen}
                modalTitle={<ModalTitle />}
                modalContent={<ModalContent />}
            />
        </div>
    );
```