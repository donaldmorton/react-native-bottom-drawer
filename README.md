# react-native-bottom-drawer


## Install
```bat
npm install react-native-bottom-drawe --save
```

## Demo
![](https://media.giphy.com/media/xUA7bcy8vCb27N67N6/giphy.gif)

## Basic example
```
 <Drawer
    initialDrawerSize={0.10}
    onDragDown={this.onDragDown.bind(this)}
    renderContainerView={()=><View style={{flex:1}}></View>}
    renderHandle={()=><Header></Header>}
    renderDrawerView={()=>(
    <View style={{height:'100%',backgroundColor:'rgba(0, 0, 0, 0.51)'}}>
       <Content>
          <List dataArray={items} renderRow={(data) =>
                <ListItem>
                   <Text>{data}</Text>
                </ListItem>
             } />
          </Content>
    </View>)}
 />

```
