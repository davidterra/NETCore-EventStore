# NETCore-EventStore

Ao usar o package **EventStore.Client** da versão 20.10.0 estava ocorrendo uma exceção ao executar o método **AppendToStreamAsync**.

> Exception has occurred: CLR/EventStore.ClientAPI.Exceptions.ConnectionClosedException
> An exception of type 'EventStore.ClientAPI.Exceptions.ConnectionClosedException' occurred in > System.Private.CoreLib.dll but was not handled in user code: 'Connection 'ES-4010513c-1f56-47f6-a681-c1e89ca98fe0' > was closed.'

Para conseguir avançar no projeto e não disparar a exceção foi preciso usar o **EventStore.Client** da versão 5.8.0.
