using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Light : MonoBehaviour
{
    public GameObject Model;
    
    void Update()
    {
        transform.LookAt(Model.transform);
    }
}
