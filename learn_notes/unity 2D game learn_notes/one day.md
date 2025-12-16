1.在Inspector中可在Renderer的目标类型替换目标模样。
2.若要导入大量同类型素材，可将素材格式化至同一图片后用unity的Inspector_sprites editor_slice进行格式分割。
3.将Script托入对象的Inspector中即可将二者关联，Script中的public对象可在unity的Inspector中操作。
4.Inspector中scale和flip可对对象翻转（可用与动画）
    getcomponent<groupname>可获取script所挂载对象的其他组件
    SpriteRenderer sr;
    sr=GetComponent<SpriteRenderer>();
    sr.flipX=false;
    sr.flipY=true;